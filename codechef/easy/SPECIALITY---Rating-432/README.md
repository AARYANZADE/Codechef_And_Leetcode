# SPECIALITY - Rating 432

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-08T14:47:05.332Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int t;
    cin >> t;

    while (t--) {
        int x, y;
        cin >> x >> y;

        int disposable_cost = 100 * x;
        int cloth_cost = 10 * y;

        if (cloth_cost <= disposable_cost) {
            cout << "Cloth\n";
        } else {
            cout << "Disposable\n";
        }
    }

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/SPECIALITY)