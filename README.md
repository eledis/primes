# primes
prime numbers h/w

#include <iostream>


using namespace std;
int main()
{
int i, n, p;
cin >> n;
if (n <= 0) {cout << "Error." << endl; }
for (i=3; (i <= n); ++i){
    p=i+2;
    if ((i % 2 !=0 && i % 3 !=0 && i % 5 !=0 && i & 7 !=0) && (p % 2 !=0 && p % 3 !=0 && p % 5 !=0 && p & 7 !=0)){
        cout << i << ',' << p << endl; }    
}
}
