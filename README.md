# Max_min_array.c
#include<stdio.h>
void main()

{
int n;
printf("Enter the size of an array : ");
scanf("%d",&n);
int arr[n];

for(int i=0;i<n;i++)
{
printf("Enter [%d] array element :  ",i);
scanf ("%d",&arr[i]);
}

for(int i=0;i<n;i++)
{

printf ("%d",arr[i]);
}

int max=-1;
for(int i=0;i<n;i++)
{
if(max<arr[i])
{
max=arr[i];
}
}
printf("\n\nThe maximum number in array  is %d",max);


int min='INT_MIN';
for(int i=0;i<n;i++)
{
if(min>arr[i])
{
min=arr[i];
}
}
printf("\n\nThe minimum number in array  is %d",min);




}
