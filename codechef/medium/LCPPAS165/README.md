# LCPPAS165

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Write a program to print all prime numbers in the range [$L$, $R$].

### Input Format
- The first and only line of input contains two space separated integers, $L$ and $R$ - The start and end of the range.
### Output Format
- Print on a single line, all prime numbers between $L$ and $R$ (inclusive) in increasing order with a space between them.
### Constraints
- 1 ≤ $L$, $R$ ≤ 1000
- $L$ ≤ $R$
### Sample 1:
Input
Output

```
2 11
```

```
2 3 5 7 11
```

### Explanation:

The prime numbers in the range [$2$, $11$] are: $2$, $3$, $5$, $7$ and $11$

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T14:48:57.686Z  

```c_cpp
#include <iostream>
using namespace std;

// Function to check if a number is prime, return true if num is prime else false
bool isPrime(int num) {
    
    
    if(num  == 2){
        return true;
    }
    for(int i=2; i<num; i++){
        if( num % i == 0){
            return false;
        }
        
    }
     return true;
}

// Function to print prime numbers in the range [L, R]
void printPrimesInRange(int L, int R) {
    for(int i = L; i<= R; i++){
        if(isPrime(i)){
            cout<<i<<" ";
        }
    }
}

int main() {
    int L, R;
    cin >> L >> R;

    printPrimesInRange(L, R);

    return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS165)