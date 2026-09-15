# LCPPAS74

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T15:05:10.541Z  

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

[View on CodeChef](https://www.codechef.com/problems/LCPPAS74)