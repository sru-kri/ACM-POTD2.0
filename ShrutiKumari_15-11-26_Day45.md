
#include <bits/stdc++.h>
using namespace std;

int main() {
    int a[4];
    for (int i = 0; i < 4; i++) {
        cin >> a[i];
    }
    sort(a, a + 4);
    for (int i = 0; i < 2; i++) {
        if (a[i] + a[i + 1] > a[i + 2]) {
            cout << "TRIANGLE";
            return 0;
        }
    }
    for (int i = 0; i < 2; i++) {
        if (a[i] + a[i + 1] == a[i + 2]) {
            cout << "SEGMENT";
            return 0;
        }
    }
    cout << "IMPOSSIBLE";
    return 0;
}

<img width="787" height="638" alt="image" src="https://github.com/user-attachments/assets/56e744b4-608c-4c92-b204-5497f0c11361" />
