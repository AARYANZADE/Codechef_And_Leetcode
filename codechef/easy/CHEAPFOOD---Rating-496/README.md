# CHEAPFOOD - Rating 496

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-10T14:50:07.259Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    int t;
    cin >> t;
    while (t--) {
        int x, y, z;
        cin >> x >> y >> z;

        if (z >= x + y) {
            cout << 2 << "\n";
        } else if (z >= x) {
            cout << 1 << "\n";
        } else {
            cout << 0 << "\n";
        }
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CHEAPFOOD)