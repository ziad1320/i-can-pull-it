# MyCode
## Code using c++ language 
```C++ language
#include <bits/stdc++.h>
#define ll long long
using namespace std;
void fast()
{
    ios_base::sync_with_stdio(0);
    cin.tie(0);
    cout.tie(0);
}
int main()
{
    fast();
    ll c=0,o=0,z=0;
    string s;    
    cin>>s;
    for(int i=0;i<s.size();i++){
        if(s[i]=='1'){
            o++;z=0;
        }
        else{
            z++;o=0;
        }
        if(o==7||z==7) c=1;
    }
    if(c==1) cout<<"YES"<<endl;
    else cout<<"NO"<<endl;
}
```
