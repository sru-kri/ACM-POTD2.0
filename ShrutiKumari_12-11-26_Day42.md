#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    for (int i = 1; i <= n; i++) {
        if (i % 2 == 1) {
            cout << "I hate";
        } else {
            cout << "I love";
        }
        if (i == n) {
            cout << " it";
        } else {
            cout << " that ";
        }
    }
    return 0;
};

<img width="737" height="480" alt="image" src="https://github.com/user-attachments/assets/284353dd-fe20-4cc9-a7e0-3e5de9fa61aa" />
