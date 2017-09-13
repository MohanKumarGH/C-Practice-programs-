# C-Practice-programs-
Important programs for basic knowledge of C++ langauge

#include <iostream>

using namespace std;

class A
{
  public :  int a;
    void set()
    {
        a=10;
    }
    
    void print()
    {
        cout<<"a="<<a<<endl;
    }
};

int main()
{
    class A s;
    class A *ptr;
    ptr=&s;
    s.set();
    s.print();
    ptr->set();
    ptr->print();
   cout << "Hello World" << endl; 
   
}
