#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    cout << (n * n + 1) / 2 << '\n';
    for (int i = 0; i < n; i++) {
        for (int j = 0; j < n; j++) {
            if ((i + j) % 2 == 0)
                cout << 'C';
            else
                cout << '.';
        }
        cout << '\n';
    }
    return 0;
}

<img width="995" height="403" alt="image" src="https://github.com/user-attachments/assets/7a4dc627-3ef5-45a7-aa39-57a054e26d77" />
