# LCPPAS163

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Given an integer  **N**  representing the length of the array, followed by  **N elements**  of the array,Find the longest subarray that does not contain zero.

### Input Format
- The first line of input will contain a single integer $N$, denoting the length of the input array.
- Second line of input contains $N$ space separated integers - the elements of the array.
### Output Format
- Output on a single line - the length of longest non-zero subarray.
### Sample 1:
Input
Output

```
5
3 0 1 0 4
```

```
1
```

### Explanation:

Subarrays [3], [1] and [4] are the longest non-zero subarrays, each of length 1.

### Sample 2:
Input
Output

```
6
1 2 0 3 4 5
```

```
3
```

### Explanation:

The subarray [3, 4, 5] is the longest non-zero subarray which has length 3.

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T14:17:05.207Z  

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
    
    int s=0;
    int temp=0;
    for(int i=0; i<n; i++){
        if(arr[i] != 0){
            s++;
            if(temp < s){
                temp =s;
            }
        }
        else{
            s=0;
        }
    }
    
    cout<<temp;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS163)