#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, s;
    cin >> n >> s;
    int a[100];
    int sum = 0;
    for (int i = 0; i < n; i++) {
        cin >> a[i];
        sum += a[i];
    }
    sort(a, a + n);
    if (sum - a[n - 1] <= s)
        cout << "YES";
    else
        cout << "NO";
    return 0;
}

<img width="803" height="412" alt="image" src="https://github.com/user-attachments/assets/c16edb10-5627-42f4-87e5-acfc21d12ac4" />
