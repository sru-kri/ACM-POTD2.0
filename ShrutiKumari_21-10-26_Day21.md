#include <bits/stdc++.h>
using namespace std;

int main() {
    string s;
    cin >> s;
    vector<int> nums;
    for (char c : s) {
        if (c != '+') {
            nums.push_back(c - '0');
        }
    }
    sort(nums.begin(), nums.end());
    for (int i = 0; i < nums.size(); i++) {
        if (i > 0) cout << "+";
        cout << nums[i];
    }
    cout << endl;
    return 0;
}

<img width="1033" height="433" alt="image" src="https://github.com/user-attachments/assets/b90341f3-5373-4387-a1c5-d877290b41e9" />
