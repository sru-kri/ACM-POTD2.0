
#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;
    int ans = 0;
    for (int i = 0; i < n; i++) {
        int p, q;
        cin >> p >> q;
        if (q - p >= 2) {
            ans++;
        }
    }
    cout << ans;
    return 0;
}

<img width="1081" height="385" alt="image" src="https://github.com/user-attachments/assets/8f29a1e1-36cc-408a-a3cb-c6bad1f96a2c" />
