# demo
#include<iostream>
using namespace std;
int main(){
    int a,b;
    char opertr;            
    cout<<"enter the two numbers";
    cin>>a>>b;
    cout<<"Enter the opertor which you wants to perform (+,-,*,%,/)";
    cin>>opertr;
    switch(opertr){
        case '+':
        cout<<"sum is "<<a+b<<endl;
        break;
        case '-':
        cout<<"subtraction is "<<a-b<<endl;
        break;
        case '*':
        cout<<"multiplication is "<<a*b<<endl;
        break;
        case '%':
        cout<<"remainder is "<<a%b<<endl;
        break;
        case '/':
        cout<<"Division is "<<a/b<<endl;
        break;
        default:
        cout<<"error";
    }
    return 0;
}
this is just a demo calculator
