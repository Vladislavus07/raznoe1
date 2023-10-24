# raznoe1

#include <iostream>
int main()
{
    int a;
    std::cin >> a;
    if (a % 3 != 0)
        std::cout << (a/3)*2+1;
    else
        std::cout << (a/ 3)*2;
    return 0;
}
