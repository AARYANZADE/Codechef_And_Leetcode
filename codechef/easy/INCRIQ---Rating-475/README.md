# INCRIQ - Rating 475

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-09T15:09:31.181Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    // Fast I/O
    ios_base::sync_with_stdio(false);
    cin.tie(NULL);

    int t;
    cin >> t;
    while (t--) {
        long long x, y, z;
        cin >> x >> y >> z;
        
        // Total seats available across 10 airplanes
        long long total_seats = 10 * x;
        
        // Number of people who can actually book is limited by total_seats
        long long booked_passengers = min(y, total_seats);
        
        // Total earnings
        long long earnings = booked_passengers * z;
        
        cout << earnings << "\n";
    }

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/INCRIQ)