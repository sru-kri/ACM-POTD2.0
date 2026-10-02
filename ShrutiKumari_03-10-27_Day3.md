#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    vector<int> a(n);
    for (int &x : a) cin >> x;
    sort(a.begin(), a.end());
    for (int i = 1; i < n; i++) {
        if (a[i] != a[0]) {
            cout << a[i] << '\n';
            return 0;
        }
    }
    cout << "NO\n";
    return 0;
}
