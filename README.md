# Classes-and-objects-

#include <iostream>


class Box
{
public:
double length;  
double breadth;  
double height;   
};

void main( )
{
Box Box1;        
Box Box2;        

double volume = 0.0;     
 

Box1.height = 5.0; 
Box1.length = 5.0; 
Box1.breadth = 3.0;


Box2.height = 10.0;
Box2.length = 5.0;
Box2.breadth = 3.0;


volume = Box1.height * Box1.length * Box1.breadth;
cout << "Volume of Box1 : " << volume <<endl;

volume = Box2.height * Box2.length * Box2.breadth;
cout << "Volume of Box2 : " << volume <<endl;
   
getch();
}
