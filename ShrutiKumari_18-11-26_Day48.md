
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;  
  int ans = 0;
    for (int i = 1; i <= n; i++) {
        int cnt = 0;
        for (int j = 2; j <= i; j++) {
            if (i % j == 0) {
                bool prime = true;
                for (int k = 2; k * k <= j; k++) {
                    if (j % k == 0) {
                        prime = false;
                        break;
                    }
                }
                if (prime) {
                    cnt++;
                }
            }
        }
        if (cnt == 2) {
            ans++;
        }
    }
    cout << ans << endl;
    return 0;
}

