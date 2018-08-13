#include<iostream.h>
#include<conio.h>

void insort(int[], int);  // function  prototype
void main()
{
	clrscr();
	int a[10], s, in;
	cout<<"\n enter size : ";
	cin>>s;   //size of array
	cout<<"\n enter the elemnts : ";
	for(int i =0;i<s;i++)
		cin>>a[i];       // enter elements
	insort(a,s);    // function calling
	getch();
}

void insort(int a[], int s)     // function defination
{
	int temp,j,i;
	 for(i = 1; i < s; i++)
	 {
		temp = a[i];
		j =i-1;
		while(temp<a[j] && j>=0)
		{
			a[j+1]= a[j];
			j--;
		}
		a[j+1] = temp;
	}

	 cout<<"\n array : ";
	 // display array
	 for(int k=0;k<s;k++)
	 cout<<a[k]<<" " ;
}