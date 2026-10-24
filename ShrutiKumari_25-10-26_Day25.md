#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, a, b;
    cin >> n >> a >> b;
    vector<int> arthur(n + 1, 0), alexander(n + 1, 0);
    for (int i = 0; i < a; i++) {
        int x;
        cin >> x;
        arthur[x] = 1;
    }
    for (int i = 0; i < b; i++) {
        int x;
        cin >> x;
        alexander[x] = 1;
    }
    for (int i = 1; i <= n; i++) {
        if (arthur[i]) {
            cout << 1 << " ";
        } else {
            cout << 2 << " ";
        }
    }
    return 0;
}

<img width="992" height="538" alt="image" src="https://github.com/user-attachments/assets/217962eb-f771-40a1-bc52-85f852793192" />
