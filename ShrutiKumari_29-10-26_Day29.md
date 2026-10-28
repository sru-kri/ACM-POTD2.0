#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    for (int i = 0; i < n; i++) {
        int d = min(i, n - 1 - i);
        for (int j = 0; j < n; j++) {
            if (j >= n / 2 - d && j <= n / 2 + d) {
                cout << 'D';
            } else {
                cout << '*';
            }
        }
        cout << '\n';
    }
    return 0;
}

<img width="986" height="407" alt="image" src="https://github.com/user-attachments/assets/fb9c94a6-ba9a-4ded-b4c9-33dad6a3c490" />
