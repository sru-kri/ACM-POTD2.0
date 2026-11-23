
#include <iostream>
#include <vector>
using namespace std;

int main() {
    int n;
    cin >> n;
    string s;
    cin >> s;
    vector<int> pos;
    for (int i = 0; i < n; i++) {
        if (s[i] == '1') {
            pos.push_back(i);
        }
    }
    int diff = pos[1] - pos[0];
    for (int i = 2; i < pos.size(); i++) {
        if (pos[i] - pos[i - 1] != diff) {
            cout << "NO";
            return 0;
        }
    }
    cout << "YES";
    return 0;
}

<img width="813" height="562" alt="image" src="https://github.com/user-attachments/assets/587d756f-02b8-4b53-b621-55936786a30e" />
