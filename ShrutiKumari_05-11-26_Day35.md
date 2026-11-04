#include <iostream>
using namespace std;

int main() {
    int k, n, w;
    cin >> k >> n >> w;
    int total = k * w * (w + 1) / 2;
    if (total > n)
        cout << total - n;
    else
        cout << 0;
    return 0;
}

<img width="842" height="355" alt="image" src="https://github.com/user-attachments/assets/8ebcc31c-a647-4c0f-aee4-0e545145117b" />
