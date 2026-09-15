# CSCV210A - Rating 412

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Debug this code - Football Cup

The code in the IDE is incorrect - debug the code to solve this problem!

Chef likes a football match if

- The match ends in a draw, and,
- At least one goal has been scored by either team.

Given the goals scored by both the teams as $X$ and $Y$ respectively, determine whether Chef will like the match or not.

### Input Format
- The first line of input will contain a single integer $T$, denoting the number of test cases. The description of $T$ test cases follows.
- Each test case consists of a single line of input containing two space-separated integers $X$ and $Y$ — the goals scored by each team.
### Output Format

For each test case, output $\texttt{YES}$ if Chef will like the match, else output $\texttt{NO}$.

### Sample 1:
Input
Output

```
2
1 1
0 1

```

```
YES
NO

```

### Explanation:

 **Test case $1$:**  It is a draw in which both teams have scored a goal, Chef will like this match.

 **Test case $2$:**  The game is not a draw. Hence, Chef will not like this match.

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T08:28:56.405Z  

```c_cpp
// The code below is incorrect. Debug the code to solve this problem
#include <bits/stdc++.h>

using namespace std;
int main()
{
    int t;
    cin >> t;
    while (t--)
    {
        int X, Y;
        //Accept 2 integers inputs.
        cin >> X >> Y;
        if (X == Y && X>0 && Y>0)
        {
            cout << "Yes" << endl;
        }
        else
        {
            cout << "No" << endl;
        }
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CSCV210A)