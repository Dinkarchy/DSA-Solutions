# BMCV204A - Rating 249

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Practice problem - Squats

Some more practice problems for you to do yourself.

You decided to do $X$ sets of squats at the gym today.
Each set consists of $15$ squats.
Determine the total number of squats that you did today.

### Input Format
- The first line contains a single integer $T$ — the number of test cases. Then the test cases follow.
- The first and only line of each test case contains an integer $X$ — the total number of sets of squats that you did.
### Output Format

For each test case, output the total number of squats done.

### Sample 1:
Input
Output

```
3
1
4
99

```

```
15
60
1485

```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:47:53.833Z  

```c_cpp
// Update the code below to solve the problem
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int t;
    cin >> t;
    while (t--)
    {
        int X, Y;
        cin >> X;


    cout<<X*15<<endl;

    }
    
}
```

---

[View on CodeChef](https://www.codechef.com/problems/BMCV204A)