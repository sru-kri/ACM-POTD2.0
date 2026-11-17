
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, m;
    cin >> n >> m;
    vector<pair<int, int>> v(m);
    for (int i = 0; i < m; i++) {
        cin >> v[i].first >> v[i].second;
    }
    sort(v.begin(), v.end(), [](auto a, auto b) {
        return a.second > b.second;
    });
    long long ans = 0;
    for (int i = 0; i < m; i++) {
        int take = min(n, v[i].first);
        ans += 1LL * take * v[i].second;
        n -= take;
        if (n == 0) break;
    }
    cout << ans << endl;
    return 0;
}

<img width="943" height="672" alt="image" src="https://github.com/user-attachments/assets/819b23d1-ec82-4abb-970b-7dfa08edf817" />
