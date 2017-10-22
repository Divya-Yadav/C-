//C++ program of leap year program by logical operators
#include<iostream>
#include<conio.h>
using namespace std;
int main()
{
	int y;
	cout<<"Enter year	:	";
	cin>>y;
	if(y%4==0 && y%400==0 || y%100!=0)
		cout<<"leap year";
	else
		cout<<"not leap year";
	return 0;
}
