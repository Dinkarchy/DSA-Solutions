# SUBSCRIBE_ - Rating 500

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-08T10:36:52.044Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	int t;
	cin>>t;
	while(t--){
	    double a,b,c;
	    cin>>a>>b>>c;
	    
	    double k = (a+b)/2;
	    
	    if(k>c){
	        cout<<"YES"<<endl;
	    }
	    else{
	        cout<<"NO"<<endl;
	    }
	}

}

```

---

[View on CodeChef](https://www.codechef.com/problems/SUBSCRIBE_)