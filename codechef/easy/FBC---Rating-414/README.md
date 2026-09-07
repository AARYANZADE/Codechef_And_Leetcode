# FBC - Rating 414

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-07T14:55:31.702Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
int t ;
cin >> t ;
while(t--){
    int x, y , z , a  ;
    cin >> x >> y ;
    z = x - y ;
    a = x + (x/10);
    cout<< a - z << endl ;
}
}

```

---

[View on CodeChef](https://www.codechef.com/problems/FBC)