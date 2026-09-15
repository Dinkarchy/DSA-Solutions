# BMCV205 - Rating 257

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Practice problem - Tuition fees

Let's solve this practice problem.

You will attend tuitions for $X$ weeks, and the cost of tuition per week is $Y$ dollars.
You need to compute and output your total  **tuition fees**.

 **Hint** 

- Refer to the multiplication syntax you learnt in the previous questions
- Run your code on the sample test cases before submitting the same
### Input Format
- The first line of input will contain an integer $T$ — the number of test cases.
- The first and only line of each test case contains two space-separated integers $X$ and $Y$
### Output Format
- For each test case, output on a new line your total tuition fees.
### Sample 1:
Input
Output

```
4
1 10
1 15
2 10
2 15
```

```
10
15
20
30

```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:21:38.932Z  

```c_cpp
//Update the code below to solve the problem
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int t;
    cin >> t;
    while (t--)
    {
        int X, Y, tuition;
        cin >> X >> Y;
        // Add some code here.
        tuition = X*Y;
        cout<<tuition<<endl;
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/BMCV205)