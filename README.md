#include <iostream>
using namespace std;
int main() 
{
    while(1){
    int randomnumber,guessnumber;

        cout<<"Enter Any Random Number Between 1 to 5 = ";
        cin>>randomnumber;
    
    guessnumber=rand()%5;
    if(guessnumber==randomnumber){
        cout<<"Congratulatation You Won The Game :)" <<endl;
    }
    else{
        cout<<"lost :(  Try Again" <<endl;
    }
    
}
}
