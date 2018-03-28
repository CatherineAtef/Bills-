# Bills-
Simply it counts your money 
#include <iostream>

using namespace std;

int main()
{
    int x;

    cin >> x;

    int y = x/100;
    int z = x - y*100;
    int a = z/50;
    int b = z - a*50;
    int c = b /20;
    int d = b - c*20;
    int q = d/10;
    int u = d - q*10;
    int w = u /5;
    int s = u - w*5;
    int l = s/2;
    int r = s - l*2;
    int h = r/1;
    int o = r - h*1;

    cout << x << endl;
    cout << y << " nota(s) de R$ 100,00 \n";
    cout << a << " nota(s) de R$ 50,00 \n";
    cout << c << " nota(s) de R$ 20,00 \n";
    cout << q << " nota(s) de R$ 10,00 \n";
    cout << w << " nota(s) de R$ 5,00 \n";
    cout << l << " nota(s) de R$ 2,00 \n";
    cout << h << " nota(s) de R$ 1,00";


    return 0;
}
