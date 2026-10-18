#include <bits/stdc++.h>
using namespace std;

int main() {
    int y;
    cin >> y;
    y++;
    while (true) {
        string s = to_string(y);
        set<char> digits(s.begin(), s.end());
        if (digits.size() == s.size()) {
            cout << y;
            break;
        }
        y++;
    }
    return 0;
}

<img width="1183" height="398" alt="image" src="https://github.com/user-attachments/assets/cd99e7fb-120c-4cee-89f2-cd48a5f0cc7a" />
