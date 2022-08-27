# take-something-return-nothing
This is a program of functions in the way of take something return nothing type.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a;
	void lock(int a);
	printf("Enter a number a:");
	scanf("%d",&a);
	lock(a);
}
void lock(int a)
{
	if(a%5==0)
	{
		printf("Lock is disabled");
	}
	else
	{
		printf("Invalid password");
	}
}
void party(int y, int z)
{
	if(y>=z)
	{
		if(y=z)
		{
			printf("You can attend party with your family");
		}
		else
		{
			printf("You can attend party alone");
		}
	}
	else
	{
		printf("You cannot attend party");
	}
}
