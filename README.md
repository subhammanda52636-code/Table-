// For Do While Loop
#include<iostream>
using namespace std;
int main ()
{ 
    int n = 2 ;
    int i = 1 ;
    cout << " Table of "<< n << " is :\n";
    do { 
        cout << n << " * " << i << " = " << n*i << endl; i++;
    } while (i <= 10); 
}
