# Deekshitha
sample programs
// C++ program to find sum of first n terms
#include <bits/stdc++.h>
using namespace std;
 
int calculateSum(int n)
{
    // Sn = n*(4*n*n + 6*n - 1)/3
    return (n * (4 * n * n + 6 * n - 1) / 3);
}
 
int main()
{
    // number of terms to be included in the sum
    int n = 4;
 
    // find the Sn
    cout << "Sum = " << calculateSum(n);
 
    return 0;
}
