#include <iostream>
using namespace std;
/**Write a program to find and print the first perfect square (i*i) whose last two digits 
are both odd.*/ 

int main(){
int i = 1;
int square, digit;
while(true){
square = i*i;
digit = (square %100)/10 ;
if(digit%2==1){
cout  <<"perfect square ending in two odd digits is: "<< square <<endl;
    break;
}

i+=2;
}

return 0;

}
