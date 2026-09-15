# GSCV211

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Test cases with multiple types of input

Listen

In the previous problem, each `testcase` had 2 lines of input - each consisting of integers.
`Test cases` can also contain a combination of `integers` and `strings`.

### Task

Let's write a program in the IDE which performs the following

- The 1st line of input contains t - the count of testcases Each testcase consists of the following 2 lines of input The 1st line of the testcase contains 2 integers - accept them as variables A and B The 2nd line of the testcase contains 1 string - accept it as a variable S
- For each test case, output on one line the 2 integers followed by the string
### Sample 1:
Input
Output

```
2
4 6
qwerty
93 123
Q1W2E3 
```

```
4 6 qwerty
93 123 Q1W2E3
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:01:35.048Z  

```c_cpp
// Write out the syntax in the blanks below
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
        int A, B;
        string S;
        //accept 2 integers on the 1st line of each test case
        cin>> A >> B;
        //accept 1 string on the 2nd line of each test case
        cin>> S;
        //output the 2 integers and a string on a single line for each test case 
        cout<< A << " " << B << " " << S << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV211)