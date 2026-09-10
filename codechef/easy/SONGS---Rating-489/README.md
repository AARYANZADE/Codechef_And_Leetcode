# SONGS - Rating 489

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-10T14:37:18.781Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    int t;
    cin >> t;
    while (t--) {
        int a, b, c;
        cin >> a >> b >> c;

        if (a > b + c || b > a + c || c > a + b) {
            cout << "YES\n";
        } else {
            cout << "NO\n";
        }
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/SONGS)