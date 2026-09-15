# LCPPAS167

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Write a program to calculate the sum of the digits present in an alphanumeric string.

### Input Format
- The first line contains an integer, T, denoting the number of test cases.
- Each of the next T lines contains a string consisting of lowercase/uppercase English letters, along with digits 0 to 9. (There shall be no space in the string)
### Output Format
- For each test case, print the sum of digits in each string.
### Constraints
- 1 ≤ T ≤ 20
- 1 ≤ Length of each string ≤ 1000
### Sample 1:
Input
Output

```
1
Hel#284!lo23Chef
```

```
19
```

### Explanation:

2 + 8 + 4 + 2 + 3 = 19

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T15:05:08.524Z  

```c_cpp
#include <bits/stdc++.h>
#include <string>
using namespace std;

int main() {
    int t;
    cin>>t;
    while(t--){
        string s;
        cin>>s;
        
        int sum =0;
        for( auto ch : s){
            if(isdigit(ch)){
                sum += ch - '0';
            }
        }
        
        
        cout<<sum<<endl;
    }
    
    return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS167)