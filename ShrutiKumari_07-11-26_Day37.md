#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, m;
    cin >> n >> m;
    vector<bool> bulbs(m + 1, false);
    for (int i = 0; i < n; i++) {
        int x;
        cin >> x;
        for (int j = 0; j < x; j++) {
            int y;
            cin >> y;
            bulbs[y] = true;
        }
    }
    for (int i = 1; i <= m; i++) {
        if (!bulbs[i]) {
            cout << "NO";
            return 0;
        }
    }
    cout << "YES";
    return 0;
}

<img width="822" height="503" alt="image" src="https://github.com/user-attachments/assets/9b091d79-494f-45d7-aca2-863bc1a0564a" />
