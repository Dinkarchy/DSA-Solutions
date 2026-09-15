# GSCV208

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### How to accept string inputs

Lets try the same exercise with strings.
Solve the problem in the IDE and then click on  **Submit**  to proceed.

### Task

You need to write a program which does the following

- Accepts $2$ space separated alphanumeric strings as input in $1^{st}$ line as the variables $A$, $B$
- Accepts $3$ space separated alphanumeric strings as input in $2^{nd}$ line as the variables $C$, $D$, $E$
- Accepts $4$ space separated alphanumeric strings as input in $3^{rd}$ line as the variables $F$, $G$, $H$, $I$
- Prints out $9$ space separated strings as output in a single line to the console
### Sample 1:
Input
Output

```
abc cde
fg hi jk
l m n o
```

```
abc cde fg hi jk l m n o
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T03:51:22.541Z  

```c_cpp
// Update the '_' in the code below
#include <bits/stdc++.h>

using namespace std;

int main()
{
    string A, B, C, D, E, F, G, H, I;
    cin >> A >> B;
    cin >> C >> D >> E;
    cin >> F >> G >> H >> I;
    cout << A << " " << B << " " << C << " " << D << " " << E << " " << F << " " << G << " " << H << " " << I;
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV208)