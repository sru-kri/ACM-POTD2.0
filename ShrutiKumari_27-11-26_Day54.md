
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, k;
    cin >> n >> k;
    string s;
    cin >> s;
    int i = 0;
    while (i < n - 1) {
        int next = -1;
        for (int j = i + 1; j <= min(i + k, n - 1); j++) {
            if (s[j] == '.') {
                next = j;
            }
        }
        if (next == -1) {
            cout << "NO";
            return 0;
        }
        i = next;
    }
    cout << "YES";
    return 0;
}

<img width="922" height="690" alt="image" src="https://github.com/user-attachments/assets/e454325c-fcc8-422b-a3b1-cc32f4c7a3a4" />

