# GSCV206

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### How to accept multiple inputs in a line

Sometimes - we have to accept multiple inputs in a single line.
We can use the same syntax to accept multiple inputs in a single line, however the different inputs will be separated by a  **'>>'**  operator.

The syntax for the same is as follows -

```
 cin >> a >> b >> c;   # assigns input values to variables a, b and c

```

Now lets try and solve the following

- Accept 3 space separated integers given in a line into 3 variables - $A$, $B$ and $C$
- Print them out to a single line on the console

You can play around with the exact syntax in the IDE -> refer to the solution in case you are unable to get this correct.
Code the solution in the IDE and then click  **Submit**  to continue.

### Sample 1:
Input
Output

```
1 2 3
```

```
1 2 3
```

### Sample 2:
Input
Output

```
1 23 456
```

```
1 23 456
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T03:46:08.417Z  

```c_cpp
// replace the '_' with the correct syntax
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int A, B, C;
    cin >>A>>B>>C;
    cout << A << " " << B << " " << C;
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV206)