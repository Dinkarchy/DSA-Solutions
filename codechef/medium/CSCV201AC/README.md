# CSCV201AC

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Logical operators

Let us try an example with multiple conditions which can be clubbed into a single  **if / else**  condition using " **and** " and " **or** ".

### Task

You are given 2 integers $A$ and $B$.
You need to compute and output the following for each test case

- If $A$ is not equal to $B$ and $A$ and $B$ are both odd - then output 'A and B are different and are odd'
- Else if $A$ is not equal to $B$ and $A$ and $B$ are both even - then output 'A and B are different and are even'
- For every other value of $A$ and $B$, output 'Doesn't matter'

Solve this problem in the IDE.

### Sample 1:
Input
Output

```
4
-9 5
3 3
-10 10
2 1
```

```
A and B are different and are odd
Doesn't matter
A and B are different and are even
Doesn't matter
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T07:54:47.650Z  

```c_cpp
// Update the '_'s below to solve the problem
#include <bits/stdc++.h>

using namespace std;
int main() {
    // your code goes here
    int t;
    cin >> t;
    while (t--)
    {
        int A, B;
        cin >> A >> B;
        if (A != B && (A % 2 != 0 && B % 2 != 0))
            cout << "A and B are different and are odd" << endl;
        else if (A != B && (A % 2 == 0 && B % 2 == 0))
            cout << "A and B are different and are even" << endl;
        else
            cout << "Doesn't matter" << endl;
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CSCV201AC)