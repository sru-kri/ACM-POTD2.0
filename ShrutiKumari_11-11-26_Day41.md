#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    int a[n];
    for (int i = 0; i < n; i++) {
        cin >> a[i];
    }
    int cnt = 1, ans = 1;
    for (int i = 1; i < n; i++) {
        if (a[i] > a[i - 1]) {
            cnt++;
        } else {
            cnt = 1;
        }
        ans = max(ans, cnt);
    }
    cout << ans << endl;
    return 0;
}

<img width="843" height="462" alt="image" src="https://github.com/user-attachments/assets/af80a1e2-7e94-4e6f-9626-de9036cd8293" />
