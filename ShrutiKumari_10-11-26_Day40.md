#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    vector<pair<int, int>> a(n);
    for (int i = 0; i < n; i++) {
        cin >> a[i].first;
        a[i].second = i + 1;
    }
    sort(a.begin(), a.end());
    for (int i = 0; i < n / 2; i++) {
        cout << a[i].second << " " << a[n - 1 - i].second << endl;
    }
    return 0;
}

<img width="787" height="462" alt="image" src="https://github.com/user-attachments/assets/aaef1bda-4b47-45b2-b22a-ac03d7c66454" />
