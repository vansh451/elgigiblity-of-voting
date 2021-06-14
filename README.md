#include<iostream>
using namespace std;
  
 int main()
  {
  
    int age;
    cout<<"Enter Your age : ";
    cin>>age;
  
    cout<<endl;
  
    if(age >= 18)
    {
        cout<<"You are egligible to vote"<<endl;
    }
  
    else if(age <= 0 || age >= 100)
    {
        cout<<"Invalid age"<<endl;
        cout<<"Try inputing valid age";
    }
  
    else{
        cout<<"You are not egligible to vote"<<endl;
        cout<<"Try again later!!";
    }
  
    return 0;
  
  }
