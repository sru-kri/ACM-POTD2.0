#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    set<pair<string, string>> s;
    for (int i = 0; i < n; i++) {
        string species, color;
        cin >> species >> color;
        s.insert({species, color});
    }
    cout << s.size();
    return 0;
}

<img width="1017" height="413" alt="image" src="https://github.com/user-attachments/assets/f5de9319-71ad-4c73-b2a4-17aa2096ec5f" />
