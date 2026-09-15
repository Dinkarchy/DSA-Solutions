# LCPPAS160

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Write a program to accept as input the length and all the elements of an array

You need to output the difference between the sum of all the even index elements and the sum of the odd index elements.

### Sample 1:
Input
Output

```
5
1 2 3 4 5
```

```
3
```

### Explanation:

1 + 3 + 5 - (2 + 4) = 3

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T14:11:53.703Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
	int n;
	cin>>n;
	
	int arr[n];
	
	for(int i=0; i<n; i++){
	    cin>>arr[i];
	}
	
	int even =0;
	int odd =0;
	for(int i=0; i<n; i++){
	    if(i%2==0){
	        even+= arr[i];
	    }
	    
	    else{
	        odd += arr[i];
	    }
	}
	
	cout<<even-odd;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS160)