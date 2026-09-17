# SUGARCANE - Rating 562

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-17T13:43:30.782Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	int t;
	cin>>t;
	while(t--){
	    int a,b,x,y;
	    cin>>a>>b>>x>>y;
	    
	    if((a*b)<=(x*y)){
	        cout<<"YES"<<endl;
	    }
	    else{
	        cout<<"NO"<<endl;
	    }
	}

}

```

---

[View on CodeChef](https://www.codechef.com/problems/SUGARCANE)