# GSCV209

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### What are test cases

Listen

In the previous problem - we wrote the program to accept 5 inputs on 5 separate lines.

- What will we do if we expect 100 inputs or test cases?
- What about 100,000 inputs or test cases?
### Task

Let's solve a simple problem.
Write a program in the IDE which does the following

- Accepts the count of test cases - t - as an integer input given in the 1st line. This is followed by t lines - Each line contains an integer N
- For each test cases, prints out the integer N to console on a separate line (our Input mirror problem)
### Sample 1:
Input
Output

```
3
1
22
33
```

```
1
22
33
```

### Explanation:

Since the count of test cases is 3 -> we accept 3 inputs and print 3 outputs

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T03:56:23.788Z  

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
        //accept an integer N in each test case
        cin>> N;
        //output the number mirror for each test case
        cout<< N<<endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV209)