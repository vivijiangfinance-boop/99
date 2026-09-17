# 99
//while
#include <iostream>
using namespace std;
int main()
{
    int a = 1;
    while (a < 10)
    {
        cout << a << "*1=" << a * 1 << "  ";
        int b = 2;
        while (b <= a)
        {
            cout << a << "*" << b << "=" << b * a << "  ";
            b++;
        }
        cout << endl;
        a++;
    }
    return 0;
}



//for
#include <iostream>
using namespace std;

int main()
{
    for (int a = 1; a < 10; a++)
    {
        for (int b = 1; b <= a; b++)
        {
            cout << b << "*" << a << "=" << a * b << "  ";
        }
        cout << endl;   // 内层循环结束后换行
    }
    return 0;
}
