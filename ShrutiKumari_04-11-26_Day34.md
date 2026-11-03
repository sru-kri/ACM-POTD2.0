#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    string s;
    cin >> s;
    set<char> st;
    for (int i = 0; i < n; i++) {
        st.insert(tolower(s[i]));
    }
    if (st.size() == 26)
        cout << "YES";
    else
        cout << "NO";
    return 0;
}

<img width="784" height="481" alt="image" src="https://github.com/user-attachments/assets/60653037-6a0f-40e0-aa7e-83da22a46ca4" />
