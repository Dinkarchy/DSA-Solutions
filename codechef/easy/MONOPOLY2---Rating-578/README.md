# MONOPOLY2 - Rating 578

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Monopoly

There are $4$ companies in the markets of Chefland, $A$, $B$, $C$, and $D$. $\\$ This year,

- Company $A$ made a profit of $P$ lakh rupees,
- Company $B$ made a profit of $Q$ lakh rupees,
- Company $C$ made a profit of $R$ lakh rupees,
- Company $D$ made a profit of $S$ lakh rupees.

There is said to be a  **monopoly**  in the market if the profit made by one company is  **strictly greater than**  the sum of profits made by all other companies. $\\$ Determine if there is a monopoly in the market or not.

### Input Format
- The first line of input will contain a single integer $T$, denoting the number of test cases.
- The first line and only line of each test case contains four space-separated integers $P$, $Q$, $R$ and $S$ — the profits made by companies $A$, $B$, $C$ and $D$ respectively.
### Output Format

For each test case, output `YES` if there is a monopoly in the market. Otherwise, output `NO`.

You may print each character of `YES` and `NO` in uppercase or lowercase (for example, `yes`, `yEs`, `Yes` will be considered identical).

### Constraints
- $1 \leq T \leq 5000$
- $1 \leq P, Q, R, S \leq 100$
### Sample 1:
Input
Output

```
4
1 1 1 10
30 20 6 4
100 90 3 4
14 15 16 17

```

```
YES
NO
YES
NO

```

### Explanation:

 **Test Case 1:**  Here, company $D$'s profit ($10$) is greater than the sum of profits of all other companies ($1 + 1 + 1 = 3$).

 **Test Case 2:**  Here, no company's profit is  **strictly**  greater than the sum of profits of all other companies.

 **Test Case 3:**  Here, company $A$'s profit ($100$) is greater than the sum of profits of all other companies ($90 + 3 + 4 = 97$).

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-25T17:42:41.155Z  

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

[View on CodeChef](https://www.codechef.com/problems/MONOPOLY2)