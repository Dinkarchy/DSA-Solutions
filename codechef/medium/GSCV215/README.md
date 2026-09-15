# GSCV215

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:10:45.567Z  

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

[View on CodeChef](https://www.codechef.com/problems/GSCV215)