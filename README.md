# Find-the-9s
#for loop
#include<iostream>
using namespace std;
int main()
{
	int sum=0;   //declaring variables with datatype integer
	cout << "Numbers divisible by 9 are :\n " << endl;
	for (int n = 100; n <= 200; n++)  //using for loop
	{
		if (n % 9 == 0)   
		{
			cout <<  n << endl;  //displaying all the numbers divisible by 9 from 100-200  
			sum = sum + n;    //adding all the numbers divisible by 9
		}
		
	}
	cout << "\nSum of all the numbers divisible by 9 = " << sum << endl;   ///displaying sum
	return 0;
}
