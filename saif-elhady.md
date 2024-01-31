#include <iostream>
#include <cmath>
#include <algorithm>
#include <bits/stdc++.h>
#include <string>
using namespace std;

#define ll long long

int main()
{
    int n;
    int sum;
    cin >> n;

    while (n)
    {
        sum += n;
        n--;
    }

    cout << sum << endl;

    return 0;
}

