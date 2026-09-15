# BMCV203

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Division with integer and decimal output

Let's focus a bit more on division to clarify the concept

- Division can return an integer value or decimal value, it all depends on which datatype you declare the variables as.

To get an integer output you need to declare the variables as  **`int`** :

```
int a = 3;
int b = 2;
int c = a/b;
cout<<c;

Output: 1

```

To get a decimal output you need to declare the variables as  **`double`** :

```
double a = 3;
double b = 2;
double c = a/b;
cout<<c;

Output: 1.5

```

### Task

In this problem you need to write a program which does the following

- Accepts the number of inputs / test cases as '$t$' The only line of each test case contains 2 integers - declare them as variables $A$ and $B$
- For each test case, you need to perform the following operations Create a variable $X$ - the division of $A$ by $B$ which returns a float value Create a variable $Y$ - the division of $A$ by $B$ which returns a integer value Output 2 space separated integers - $X$ and $Y$ in a single line.
### Sample 1:
Input
Output

```
2
10 4
10 6
```

```
2.5 2
1.66667 1
```

### Explanation:

 **Test case 1** : The 2 integers are $10$ and $4$ and we output $2.5$ and $2$ as the value of $X$ and $Y$ respectively

 **Test case 2** : The 2 integers are $10$ and $6$ and we output $1.66667$ and $1$ as the value of $X$ and $Y$ respectively

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:43:09.457Z  

```c_cpp
// Update the '_' below to solve the problem
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int t;
    cin >> t;
    while (t--)
    {
        double A, B, X;
        cin>> A >> B;
        //Division of A by B - float / decimal result
        X = A / B;
        int C, D, Y;
        C = A;
        D = B;
        //Division of A by B - integer result
        Y = A / B;
        cout << X << " " << Y << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/BMCV203)