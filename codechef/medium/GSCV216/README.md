# GSCV216

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Debug this code - Why is this code incorrect

Listen

Now try and debug this problem.

You are given a program in the IDE which is trying to do the following

- Accepts the count of test cases - t - in the 1st line Each line of test case consists of an integer N
- For each test case, it is supposed to print double the integer N as the output
### Sample 1:
Input
Output

```
3
1
2
3
```

```
2
4
6
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:14:08.841Z  

```c_cpp
// Debug the code below to solve the problem
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int t;
    cin >> t;
    while (t--)
    {
        int N;
        cin >> N;
    cout << 2 * N << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV216)