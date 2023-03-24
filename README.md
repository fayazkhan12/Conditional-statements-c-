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
 
