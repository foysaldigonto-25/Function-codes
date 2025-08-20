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
