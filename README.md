# the temperature Fahrenheit to Celsius 
 A program that change the temperature from fahrenheit to celsius and then celsius to farentheit 
#include<iostream>
using namespace std;
int main()
{
 char tempt;
 double temp,faren,cel;
 cout<<"enter the temperature to be converted"<<endl;
 cin>>temp;
 cout<<"enter the type of temperature f for farenhiet or c for celsius"<<endl;
 cin>>tempt;
 if(tempt=='c')
 {
 faren=(9.0/5.0)*(temp+32);
cout<<"temperature in farenhiet is = "<<faren<<endl;
}
else
{
 cel=(0.5/9.0)*(temp-332.0);
 cout<<"temperture in celsius is = "<<cel<<endl;
}
return 0;
}
