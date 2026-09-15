# GSCV210

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Test cases with multiple lines of input

Listen

In the previous problem, we had  ***`t`** * `test cases` and each `test case` had 1 line of input.
However, each `test case` can have multiple lines of input as well.

### Task

Let's write a program in the IDE which performs the following

- The 1st line of input is an integer t - the count of test cases
- Each test case consists of 2 lines of input The 1st line of input has 2 space separated integers - accept them as variables A and B The 2nd line of input has 3 space separated integers - accept them as variables C, D and E
- For each test case - output all integers on a single line
### Sample 1:
Input
Output

```
3
1 2
3 4 5
11 22
33 44 55
1 23
456 789 101112
```

```
1 2 3 4 5
11 22 33 44 55
1 23 456 789 101112
```

### Explanation:

2 lines of input in test case 1:
1 2
3 4 5

Output 1: 1 2 3 4 5

2 lines of input in test case 2:
11 22
33 44 55

Output 2: 11 22 33 44 55

2 lines of input in test case 3:
1 23
456 789 101112

Output 3: 1 23 456 789 101112

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T03:57:36.092Z  

```c_cpp
// Update the '_' below to solve the problem
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
        int A,
        B,
        C,
        D,
        E;
        //accept 2 integers on the 1st line of each test case
        cin>> A >> B;
        //accept 3 integers on the 1st line of each test case
        cin>> C >> D >> E;
        //output the 5 integers on a single line for each test case 
        cout << A << " " << B << " " << C << " " << D << " " << E << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV210)