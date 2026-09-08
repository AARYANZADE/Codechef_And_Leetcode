# TYRE - Rating 451

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-08T15:03:50.570Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    // Fast I/O
    ios_base::sync_with_stdio(false);
    cin.tie(NULL);

    int t;
    cin >> t;

    while (t--) {
        int x, y;
        cin >> x >> y;

        if (x < y) {
            cout << "REPAIR\n";
        } else if (x > y) {
            cout << "NEW PHONE\n";
        } else {
            cout << "ANY\n";
        }
    }

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/TYRE)