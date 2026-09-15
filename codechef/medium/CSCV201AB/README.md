# CSCV201AB

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Logical operators & conditional statements

We reviewed basic conditional operators in the previous module.
In this module - we will cover logical operators in conditional statements.

- "and" and "or" in statements help check multiple conditions
- A single statement can have multiple conditions clubbed together using "and" and "or". These can be used in if / else conditions.
### Task

You are given 3 integers $N$, $A$ and $B$.
You need to compute and output the following for each test case

- If $N$ is divisible by both $A$ and $B$ - then output 'N is divisible by A and B'
- Else if $N$ is divisible by $A$ and not $B$ - then output 'N is divisible by only A'
- Else if $N$ is divisible by $B$ and not $A$ - then output 'N is divisible by only B'
- Else if $N$ is divisible by neither $A$ nor $B$ - then output 'N is divisible by neither A nor B'

Solve this problem in the IDE.

### Sample 1:
Input
Output

```
4
10 5 2
10 3 2
12 3 5
10 4 3
```

```
N is divisible by A and B
N is divisible by only B
N is divisible by only A
N is divisible by neither A nor B
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T07:50:17.723Z  

```c_cpp
// Update the '_' in the code below to solve the problem
#include <bits/stdc++.h>

using namespace std;
int main() {
    // your code goes here
    int t;
    cin >> t;
    while (t--)
    {
        int N, A, B;
        cin >> N >> A >> B;
        if (N%A == 0 && N % B == 0)
            cout << "N is divisible by A and B" << endl;
        else if (N % A == 0)
            cout << "N is divisible by only A" << endl;
        else if (N % B == 0)
            cout << "N is divisible by only B" << endl;
        // The last statement could have been an 'else' statement
        // else if condition used to show usage of 'and' statement
        else if (N % A != 0 && N % B != 0)
            cout << "N is divisible by neither A nor B" << endl;
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CSCV201AB)