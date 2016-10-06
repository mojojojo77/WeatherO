# WeatherO
Weather Information

/*
#include<iostream>
#include<cstring>
using namespace std;
int main()
{
	int age;
	int income = 0;
	char city[10];
	int car;

	cout<<"\n\t Enter The Age: ";
	cin>>age;

	try
	{	
		if(age<18 || age>55)
		{
		throw age;
		}
		else
		{
			cout<<"\n\t The Age is: "<<age;
		}
	}
	catch(int)
	{
		cout<<"\n\t The Age is not between 18 and 55!!";
	}

	cout<<"\n\t Enter The Income: ";
	cin>>age;

	try
	{
		if(income<50 || income>100)
		{
		throw income;
		}
		else
		{
			cout<<"The income is: "<<income;
		}
	}
	catch(int)
	{
		cout<<"\n\t The Income is not between 50000 and 100000!!";
	}

	cout<<"\n\t Enter The City: ";
	cin>>city;

	try
	{
		if(strcmp(city,"pune")&& strcmp(city,"mumbai")&& strcmp(city,"banglore")&& strcmp(city,"channai"))
		{
		throw city;
		}
		else
		{
			cout<<"\n\t The City is: "<<city;
		}
	}
	catch(char)
	{
		cout<<"\n\t The Person Live in Nither Pune, Mumbai, Banglore nor Channai!!";
	}



	cout<<"\n\t Enter No. of Wheels of the Vheical: ";
	cin>>car;

	try
	{
		if(car!=4)
		{
		throw car;
		}
		else
		{
			cout<<"\n\t The Person Uses 4 Wheeler: ";
		}
	}
	catch(int)
	{
		cout<<"\n\t The Person do not use 4 Wheeler!!";
	}
	
	return 0;
}
*/
