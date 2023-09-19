# HackerRank_basic_data_types.cpp
Easy Problem
Data Types:
Some C++ data types, their format specifiers, and their most common bit widths are as follows:

Int ("%d"): 32 Bit integer
Long ("%ld"): 64 bit integer
Char ("%c"): Character type
Float ("%f"): 32 bit real value
Double ("%lf"): 64 bit real value
#include<bits/stdc++.h>
using namespace std;


int main() {
    int a ;
    long b ;
    char c ;
    float d ;
    double e ;
    cin>> a >> b >> c >> d >> e; 
    cout<<a<<endl;
    cout<<b<<endl;
    cout<<c<<endl;
    cout<<fixed << setprecision(3)<<d<<endl;
    cout<<fixed << setprecision(9)<<e<<endl;
    
    
    
    return 0;
}
