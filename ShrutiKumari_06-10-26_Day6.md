#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    vector<int> a(n);
    for (int i = 0; i < n; i++)
        cin >> a[i];
    int ans1 = 1;
    int ans2 = 2;
    int mn = abs(a[0] - a[1]);
    for (int i = 1; i < n; i++) {
        int j = (i + 1) % n;
        int diff = abs(a[i] - a[j]);
        if (diff < mn) {
            mn = diff;
            ans1 = i + 1;
            ans2 = j + 1;
        }
    }
    cout << ans1 << " " << ans2;
    return 0;
}
