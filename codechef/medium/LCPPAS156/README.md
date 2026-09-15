# LCPPAS156

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Write a program to input two student's names and percentages and print the name of the student with the higher percentage. In case they score equal percentages, print ' **equal** '.

### Input Format
- The first line of input will contain two strings: the name of the first student and the name of the second student.
- The second line of input will contain two percentages: the percentage of the first student and the percentage of the second student.
### Sample 1:
Input
Output

```
Amit Swarup
95 92
```

```
Amit
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T14:07:09.423Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	string a,b;
	cin>>a>>b;
	int c,d;
	cin>>c>>d;
	
	if(c>d){
	    cout<<a;
	}
	else{
	    cout<<b;
	}

}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS156)