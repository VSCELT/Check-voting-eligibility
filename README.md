# Check-voting-eligibility
Check voting eligibility



//Check voting eligibility
#include<iostream>
using namespace std;
main()
{
	int age;
	cout<<"Enter your age:\n";
	cin>>age;
	if(age<18)
	{
		cout<<"You are not eligible to cast the vote:\n";
	}
	else
	{
		cout<<"You are eligible to cast the vote:\n";
	}
}
