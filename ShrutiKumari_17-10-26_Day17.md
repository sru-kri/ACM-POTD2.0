#include <bits/stdc++.h>
using namespace std;

int main() {
    int a[4];
    for (int i = 0; i < 4; i++) {
        cin >> a[i];
    }
    sort(a, a + 4);
    int count = 0;
    for (int i = 1; i < 4; i++) {
        if (a[i] == a[i - 1]) {
            count++;
        }
    }
    cout << count << endl;
    return 0;
}

<img width="1196" height="481" alt="image" src="https://github.com/user-attachments/assets/f3868002-a8fb-4caa-897a-28176389ced4" />
