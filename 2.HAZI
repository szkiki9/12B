
#include <iostream>

using namespace std;

int main()
{
    int n, k, szam=0;
    int v[100];
    cout << "n= ";
    cin >> n;
    cout << "k= ";
    cin >> k;

    for(int i=0; i<n; i++){
       int c=0;
       cin >> v[i];
       while(v[i]!=0){
        v[i]=v[i]/10;
        c++;
       }
       if(c>k){
        szam++;
       }
    }
    cout << szam << endl;
    return 0;
}
