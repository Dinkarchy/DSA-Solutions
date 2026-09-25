# TODOLIST - Rating 578

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-25T17:42:43.512Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;
int main(){
    int T; cin>>T;
    while(T--){
        int P,Q,R,S; cin>>P>>Q>>R>>S;
        int arr[4]={P,Q,R,S};
        int sum=P+Q+R+S;
        bool ok=false;
        for(int i=0;i<4;i++){
            if(arr[i]>sum-arr[i]){ok=true;break;}
        }
        cout<<(ok?"YES":"NO")<<"\n";
    }
}

```

---

[View on CodeChef](https://www.codechef.com/problems/TODOLIST)