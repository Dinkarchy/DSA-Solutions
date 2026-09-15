# GSCV213

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Number mirror - Negative integer

Listen

Let us now solve some programming problems. Note that

- In the IDE - the text after '//' is comments which doesn't affect the code and will give you hints about what you need to do
- The Solution tab also has '//' - comments which give you helpful information
### Task

Write a program in the IDE which does the following

- Accepts the count of test cases - t - in the 1st line The only line of each test case consists of an integer N
- You need to generate the following output - Change the sign of N. That is, if the input is 4, output -4. If the input is -5, output 5.
### Sample 1:
Input
Output

```
5
1
2
3
-4
-5
```

```
-1
-2
-3
4
5
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:08:30.418Z  

```c_cpp
// Update the '_' in the code below
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int t;
    //accept the count of test cases given in the the 1st line
    cin >> t;
    //Run a loop to accept 't' inputs
    while (t--)
    {
        int N;
        //accept 1 integer on the 1st line of each test case
        cin>>N;
        //output the negative integer - i.e. (-N)
        cout << -N<< endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV213)