# FLOW002 - Rating 419

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-07T14:59:38.689Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {

    
    int t;
    cin >> t;
    while (t--) {
        int n, x;
        cin >> n >> x;
        if (2 * x >= n) {
            cout << "YES\n";
        } else {
            cout << "NO\n";
        }
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/FLOW002)