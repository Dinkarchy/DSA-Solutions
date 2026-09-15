# LCPPAS168

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T14:48:58.546Z  

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

[View on CodeChef](https://www.codechef.com/problems/LCPPAS168)