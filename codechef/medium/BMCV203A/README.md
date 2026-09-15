# BMCV203A

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Integer and decimals - Type Conversion

In the previous problem, we divided a double by a double, and stored it in a double. What happens if we mix up these data types?

Let's try dividing a double by a double, but store it in an int:

```
double a = 3;
double b = 2;
int c = a/b;
cout<<c;

Output: 1

```

We get only an integer output. This is because a/b is first computed, and it is actually a double. But when it is stored in c (which is an int), c can't store the decimal digits, and takes only the integer part.

Now let's try the opposite. Divide an int by an int and store it in a double:

```
int a = 3;
int b = 2;
double c = a/b;
cout<<c;

Output: 1

```

We still get an int, because a/b is itself only 1. So even though c can store decimal digits, those decimal digits aren't even produced at first.

Now, let's divide a double by an int and see what happens:

```
double a = 3;
int b = 2;
double c = a/b;
cout<<c;

Output: 1.5

```

Here, something called "type conversion" happens. C++ can only divide two values of the same type. So it can't do double/int. But it cleverly understands that every integer can also be represented as a double (for eg. 4 is 4.0). So it automatically converts the int into a double. And hence a/b is a double, and it's stored in a double. So the output contains the decimal part as well.

### Task

In this problem you need to write a program which does the following

- Accepts the number of inputs / test cases as '$t$' The only line of each test case contains 2 integers - declare them as variables $A$ (double) and $B$ (int)
- For each test case, you need to output $A$ divided by $B$.
### Sample 1:
Input
Output

```
2
6 4
10 3

```

```
1.5
3.33333

```

### Explanation:

 **Test case 1** : The 2 integers are $6$ and $4$ and we output $1.5$.

 **Test case 2** : The 2 integers are $10$ and $3$ and we output $3.33333$.

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T04:46:33.493Z  

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
        double A, X;
        int B;
        cin >> A >> B;
        //Division of A by B (double / int)
        X = A / B;
        cout << X << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/BMCV203A)