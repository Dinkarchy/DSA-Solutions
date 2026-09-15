# BMCV202

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Subtraction and division of numbers

While sum and addition of $2$ numbers did not require any specific precautions, we need to be careful during subtraction and division operations

- Subtraction can return a positive or negative value depending on which number is larger
- Division can return an integer or float
### Task

Write a program that does the following

- Accepts the number of inputs / test cases as 't' The only line of each test case contains 2 integers - declare them as variables $A$ and $B$
- For each test case, you need to perform the following operations Create a variable - $D$ - what you get after subtracting $B$ from $A$. Create a variable - $Q$ - the quotient when $A$ is divided by $B$ Output 2 space separated integers - $D$ and $Q$ in a single line

 **Note:**  The inputs have been created such that

- $A$ is necessarily greater than or equal to $B$
- $A$ is necessarily exactly divisible by $B$
### Sample 1:
Input
Output

```
2
10 5
16 4
```

```
5 2
12 4
```

### Explanation:

 **Test case 1** : The 2 integers are $10$ and $5$ and we output $5$ as their difference and $2$ as the quotient of their division

 **Test case 2** : The 2 integers are $16$ and $4$ - we output $12$ as their difference and $4$ as the quotient of their division

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:39:17.249Z  

```c_cpp
//  Update the '_' below to solve the problem
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int t;
    cin >> t;
    while (t--)
    {
        int A,
        B,
        D,
        Q;
        //Accept 2 integers as inputs. Note that A >= B and A is divisble by B.
        cin >> A >> B;
        //Difference of inputs
        D = A - B;
        //Division of inputs. 
        Q = A / B;
        //Print the desired output for each test case
        cout<< D << " " << Q << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/BMCV202)