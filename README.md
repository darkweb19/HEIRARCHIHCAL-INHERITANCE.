# HEIRARCHIHCAL-INHERITANCE.
Here is the CODE for # HEIRARCHIHCAL-INHERITANCE.
//CODE /c++....


//....HEIRARCHIHCAL INHERITANCE....//

#include <iostream>
using namespace std;
class A // base classs
{
public:
    void func1()
    {
        cout << "Function 1..." << endl;
    }
};
class B : public A // first derieved class from A...
{
public:
    void func2()
    {
        cout << "Function 2...." << endl;
    }
};
class C : public A // second derived  class from A
{
public:
    void func3()
    {
        cout << "Function 3..." << endl;
    }
};
// Heirarchical Inheritance .....
int main()
{
    cout << "For Class A..." << endl;
    C c1;
    c1.func1();
    // c1.func2();       // cannot be used
    c1.func3();
    cout << ".....For Class B" << endl;
    B b1;
    b1.func1();
    b1.func2();
    return 0;
}
