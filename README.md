# first
#include <iostream>
using namespace std;

int main(){
    cout <<"hello world my name is krishna"<<endl;
    int a,b;
    cout<<"enter your number :";

    cin>>a; 
    cout << a<< endl;

    switch (a)
    {
    case 18:
        cout<<"you are 18 year old";
        break;
    
    default:
        cout<<  "you are not 18 year old";
        break;
    }

    

    return 0;
}
