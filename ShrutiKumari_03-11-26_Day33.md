#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    int height = 0;
    int cubes = 0;
    int level = 1;
    while (cubes + (level * (level + 1)) / 2 <= n) {
        cubes += (level * (level + 1)) / 2;
        height++;
        level++;
    }
    cout << height << endl;
    return 0;
}

<img width="888" height="372" alt="image" src="https://github.com/user-attachments/assets/c7a7dac1-9b61-44a6-b364-d784880c7576" />
