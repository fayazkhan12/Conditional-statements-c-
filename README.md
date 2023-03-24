# Conditional-statements-c-
 profit and loss questions
 
 
 #include<iostream>
using namespace std;
int main()
{
    int cp,sp;
    int profit,loss;
    cout<<"enter the cost price and selling price \n";
    cin>>cp>>sp;
    if(sp>cp)
    {
        profit=sp-cp;
        cout<<"profit occured. of "<<profit;
    }
    else{
        loss=cp-sp;
        cout<<"loss ocurred of"<<loss;
    }
}
 
 
 
 // Divisible by 3 and 5 

#include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the number..";
    cin>>n;
    if(n%5==0)
    {
        cout<<"divisible by 5..";
        
    }
    else if(n%3==0)
        cout<<"divisible by  3 ";
    else{
        cout<<"not divisible by 3 and 5..";
    }
    
    
}

 // Given character is alphabet or not

#include<iostream>
using namespace std;
int main()
{
    char ch;
    cout<<"Enter the given character..";
    cin>>ch;
    int ascii = (int)ch;
    if(ascii>=97 && ascii<=122)
    {
        cout<<"small alphabats..";
    }
     else if(ascii>=65 && ascii<=90)
    {
    cout<<"capital letter alphabets.."; 
    }
    else{
        cout<<"no alphabetss..";
    }
    
}
 
               
               
               
               // greater among two numbers...

#include<iostream>
using namespace std;
int main()
{
    int a,b;
    cout<<"enter the two number\n";
    cin>>a>>b;
    if(a>b)
    {
        cout<<"a is greater than b..";
        
    }
    else
    {
        cout<<"b is grater..";
    }
    
    
    
}
 
 
 
 
 


// calculate area annd perimeter and tell which is greater..

#include<iostream>
using namespace std;
int main()
{int r;
int pi=3.14;

cout<<"enter the radius";
cin>>r;
 int area=pi*r*r;
     cout<<"area is =  "<<area<<endl;;
     
     int perimeter=2*pi*r;
     
     cout<<"perimeter is = "<<perimeter<<endl;
     if (area>perimeter){
         cout<<"area is greater..";
     }
     else
     {
         cout<<"perimeter is greater..";
     }
     
    
    
// check weather the character is a alphabet ,character or special character

#include<iostream>
using namespace std;
int main()
{
    char ch;
    cout<<"enter the character..";
    cin>>ch;
    
    if((ch >='a' && ch<='z') ||  (ch>='A'&& ch<='Z'))
    {
        cout<<"it is a alphabet..";
        
    }
    
    else if(ch>='0' && ch<='9')
    {
        cout<<"it is a digit..";
        
    }
    else
    {
        cout<<"it is a special character...";
    }
}    

 
 
// wap for leap year 
// leap year should be divisibe by 400 , 4  and not divisible by 100 

#include<iostream>
using namespace std;
int main()
{
    int year;
    cout<<"enter the given year..";
    cin>>year;
    if(year%400==0)
    {
        cout<<"it is a leap year.."<<year;
        
    }
    
    else if(year%100==0)
    {
        cout<<"not a leap year..";
        
    }
    else if(year%4==0)
    {
        cout<<"leap year";
        
    }
    
    else
    
    {
        cout<<"not a leap year..";
    }
} 
 
 
 
 
 
 
