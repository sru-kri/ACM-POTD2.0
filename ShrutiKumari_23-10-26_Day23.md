#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    vector<int> p(n);
    for (int i = 0; i < n; i++) {
        cin >> p[i];
    }
    int winner = 0;
    for (int i = 1; i < n; i++) {
        if (p[i] > p[winner]) {
            winner = i;
        }
    }
    int price = 0;
    for (int i = 0; i < n; i++) {
        if (i != winner && p[i] > price) {
            price = p[i];
        }
    }
    cout << winner + 1 << " " << price << endl;
    return 0;
}


<img width="907" height="552" alt="image" src="https://github.com/user-attachments/assets/49f82de9-ebda-4e40-a801-1170551d8262" />
