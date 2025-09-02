# Function-codes

1.Declaring differrent functions.

#include <iostream>
<br>
using namespace std;

void addition (int a,int b)

{
    int sum = a+b;
    cout<<"Sum :"<<sum<<endl;

}

void subtraction (int a,int b)
{

    int sum1 = a-b;
    cout<<"Multy sum :"<<sum1<<endl;

}

void division (int a,int b)

{

    float sum2 = (float) a/b;
    cout<<"Div sum :"<<sum2<<endl;

}

int main (){

    addition(40,30);
    addition(50,40);

    return 0;
}

2.Returning value from functiion...

#include <iostream>

#include <conio.h>

using namespace std;

double addition (double,double);

int main(){

    cout<<addition (30.6,50.7);


    getch();
}

double addition(double a,double b){

     double sum = a+b;
     return sum;
}

3.
#include <iostream>

using namespace std;

void calculateTriangleArea (float a,float b)
{

    float area = 0.5*a*b;
    cout<<"Area of the triangle is :"<<area<<endl;
}

void calculateRectangleArea ( float c,float d)

{

    float area = c*d;
     cout<<"Area of the rectangle is :"<<area<<endl;
}

  int main (){
  
      float a,b,c,d;
      cout<<"Enter the base and height of the triangle :\n";
      cin>>a>>b;
      calculateTriangleArea(a,b);

      cout<<"\nEnter the length and width of the rectangle :\n";
      cin>>c>>d;
      calculateRectangleArea(c,d);

      return 0;
  }


