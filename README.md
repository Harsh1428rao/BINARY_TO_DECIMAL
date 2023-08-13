# BINARY_TO_DECIMAL
BINARY TO DECIMAL USING C++
#include <iostream>
#include <cmath>

using namespace std;

int main()
{
	int n;
	int i,a[n],b=0;
	cout<<"Enter the Number of Binary Digit: ";
	cin>>n;
	for(i=0;i<n;i++)
	{
		cin>>a[i];
	}
	cout<<"Array is :\n";
	for(i=0;i<n;i++)
	{
		cout<<a[i]<<endl;
		if(a[i]==1);
		{
			b=pow(2,(n-1-i))*a[i]+b;
		}
	}
	cout<<"Decimal Number: "<<b;
	
}
