
#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;
    string s;
    cin >> s;
    int anton = 0, danik = 0;
    for (int i = 0; i < n; i++) {
        if (s[i] == 'A') {
            anton++;
        }
        else {
            danik++;
        }
    }
    if (anton > danik) {
        cout << "Anton";
    }
    else if (danik > anton) {
        cout << "Danik";
    }
    else {
        cout << "Friendship";
    }
    return 0;
}

<img width="806" height="695" alt="image" src="https://github.com/user-attachments/assets/d9dc907f-ce13-4982-909b-2eb68a80177b" />
