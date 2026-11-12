
#include <bits/stdc++.h>
using namespace std;

int main() {
    string s;
    cin >> s;
    int col = s[0] - 'a';
    int row = s[1] - '1';
    int ans = 0;
    for (int i = -1; i <= 1; i++) {
        for (int j = -1; j <= 1; j++) {
            int x = col + i;
            int y = row + j;
            if (x >= 0 && x < 8 && y >= 0 && y < 8) {
                if (i != 0 || j != 0) {
                    ans++;
                }
            }
        }
    }
    cout << ans << endl;
    return 0;
}

<img width="805" height="628" alt="image" src="https://github.com/user-attachments/assets/972dc2c5-c70b-4357-af29-6d0273374065" />
