# GSCV214

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### String mirror - Double strings

Listen

Write a program in the IDE which does the following

- Accepts the count of test cases - t - in the 1st line First line of each test case consists of a string S
- You need to perform the following operation Create a variable X which contains the string S concatenated with the string S Output X for each test case
### Sample 1:
Input
Output

```
3
ab
bc
cd
```

```
abab
bcbc
cdcd
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:10:42.952Z  

```c_cpp
//Update the '_' in the code below
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
        string S, X;
        cin >> S;
        //Store the value of string S concatenated with itself to variable X
        X = S+ S;
        cout << X << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV214)