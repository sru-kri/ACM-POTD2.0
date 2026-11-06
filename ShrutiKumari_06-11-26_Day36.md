
#include <iostream>
#include <algorithm>
using namespace std;

int main() {
    int a, b;
    cin >> a >> b;
    int x = min(a, b);
    int y = (max(a, b) - x) / 2;
    cout << x << " " << y << endl;
    return 0;
}

<img width="790" height="365" alt="image" src="https://github.com/user-attachments/assets/b322c66c-796d-4a46-905a-bf2c993b5f2a" />
