#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, ans = 0;
    string s;
    cin >> n >> s;
    for (int i = 1; i < n; i++) {
        if (s[i] == s[i - 1])
            ans++;
    }
    cout << ans << endl;
    return 0;
}

<img width="1201" height="366" alt="image" src="https://github.com/user-attachments/assets/e675d3b8-a484-4236-a240-e295f3fd1a80" />
