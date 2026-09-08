# MAXIMUMSUBS - Rating 434

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-08T14:55:33.336Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int t;
    cin >> t;

    while (t--) {
        int x, y, z;
        cin >> x >> y >> z;

        if (x > max(y, z)) {
            cout << "Setter\n";
        } else if (y > max(x, z)) {
            cout << "Tester\n";
        } else {
            cout << "Editorialist\n";
        }
    }

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/MAXIMUMSUBS)