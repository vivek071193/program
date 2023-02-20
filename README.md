# program
set new programs
#include<iostream>
using namespace std;
 
 
 //object slicing
 
 class Base
 {
     public :
     int x,y;
     
 };
 
 
 class child: public Base //derived
 {
     public:
     int z;
 };
 
 
 int main()
 {
     Base b;  //object creation b
     child c; //object creation c
     b.x=10;
     b.y=20;
     cout<<"b.x="<<b.x<<" "<<"b.y="<<b.y<<endl;
     
     c=b;
     cout<<"c.x="<<c.x<<"c.y="<<c.y<<endl;

     
     
    /* c.x=100;
     c.y=120;
     c.z=130;
     cout<<"c.x="<<c.x<<"c.y="<<c.y<<"c.z="<<c.z<<endl;
     
     b=c; //assingning from c values to b
     cout<<"b.x="<<b.x<<" "<<"b.y="<<b.y<<endl; */

     
     return 0;
 }
