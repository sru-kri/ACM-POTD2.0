#include <bits/stdc++.h>
using namespace std;

int main() {
    string s;
    getline(cin, s);
    int i = s.size() - 1;
    while (!isalpha(s[i])) {
        i--;
    }
    char c = tolower(s[i]);
    if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u' || c == 'y')
        cout << "YES";
    else
        cout << "NO";
    return 0;
}
