# F1RULE - Rating 483

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-10T14:30:08.321Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
int t ;
cin >> t ;
while (t--){
    int a , b , c , d, e , f  ;
    cin >> a >> b >> c >> d ;
    e = b - a ;
    f = c * d ;
    if (e > f ){
        cout << "unfilled"<<endl;
    }
    else if (e<f) {
        cout <<"overflow"<<endl;
    }
    if (e == f){
        cout << "filled"<<endl;
    }
}
}

```

---

[View on CodeChef](https://www.codechef.com/problems/F1RULE)