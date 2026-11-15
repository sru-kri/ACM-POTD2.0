
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, d;
    cin >> n >> d;
    vector<long long> a(n);
    for (int i = 0; i < n; i++) {
        cin >> a[i];
    }
    long long ans = 0;
    for (int i = 1; i < n; i++) {
        if (a[i] <= a[i - 1]) {
            long long moves = (a[i - 1] - a[i]) / d + 1;
            ans += moves;
            a[i] += moves * d;
        }
    }
    cout << ans << endl;
    return 0;
}

<img width="891" height="665" alt="image" src="https://github.com/user-attachments/assets/94b69b4b-1eba-4489-8900-67b85ccf38b9" />
