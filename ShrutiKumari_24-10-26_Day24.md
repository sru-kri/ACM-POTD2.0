#include <bits/stdc++.h>
using namespace std;

int main() {
    string s;
    cin >> s;
    bool upper = false, lower = false, digit = false;
    for (char c : s) {
        if (c >= 'A' && c <= 'Z') upper = true;
        if (c >= 'a' && c <= 'z') lower = true;
        if (c >= '0' && c <= '9') digit = true;
    }
    if (s.size() >= 5 && upper && lower && digit)
        cout << "Correct";
    else
        cout << "Too weak";
    return 0;
}

<img width="860" height="402" alt="image" src="https://github.com/user-attachments/assets/b2d14fe8-8d5a-4902-aa6c-44fce9bb5ef2" />
