# Check-Age-for-Voting
I've tried using  some decision making statement's and completed it , Hope you'll like it!!
And so below here goes the code captain !!

//C++ PROGRAM TO CHECK AGE OF A USER WHETHER HE/SHE IS ELIGIBLE TO VOTE OR NOT .


#include<iostream.h>
#include<conio.h>
void main()
{
	int a,age,choice;
	clrscr();
	cout<<"Enter any number if you are not a robot and wanna vote:-";
	cin>>a;
	if(a>=0)
{
	cout<<"\n Great!! Please Enter your age:-";
	cin>>age;

		if(age>=18)
		{
		cout<<"\nYou are eligible to vote\n";
		cout<<"We appreciate your valuable presence\n";
		}

		else
{
		cout<<"You are not eligible to vote\n";
		cout<<"Better Luck Next Time";
}
}
	if(age>=18)
	{
	cout<<endl<<"The Volunteer's Standing On Elections are as follows:-";
	cout<<"\n1-> Mr X";
	cout<<"\n2-> Mrs Y";
	cout<<"\n3-> Mr Z\n";
	cout<<"Please enter your choice to vote:-";
	cin>>choice;
	switch(choice)
	{
		case 1:
			cout<<"Thanks For Voting Mr X \n Hope Sir win's :) ";
			break;
		case 2:
			cout<<"Thanks For Voting Mrs Y \n Hope Mam win's :)";
			break;
		case 3:
			cout<<"Thanks For Voting Mr Z \n Hope Sir win's :)";
			break;
	}
	}
	getch();
}


