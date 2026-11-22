#include <bits/stdc++.h>
using namespace std;

int main() {
    string s;
    cin >> s;
    int count = 1;
    for (int i = 1; i < s.size(); i++) {
        if (s[i] == s[i - 1]) {
            count++;
        } else {
            count = 1;
        }
        if (count >= 7) {
            cout << "YES";
            return 0;
        }
    }
    cout << "NO";
    return 0;
}

<img width="822" height="567" alt="image" src="https://github.com/user-attachments/assets/4c04a147-16b9-4749-993c-981b75a88936" />
