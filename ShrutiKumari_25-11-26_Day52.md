#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    while (n--) {
        long long a, b;
        cin >> a >> b;
        long long ans = 0;
        while (a > 0 && b > 0) {
            ans += a / b;
            a %= b;
            swap(a, b);
        }
        cout << ans << '\n';
    }
    return 0;
}


<img width="770" height="526" alt="image" src="https://github.com/user-attachments/assets/410ce8da-ef00-4a09-bf37-cee4e5056cbb" />
