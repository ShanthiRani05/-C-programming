#include<stdio.h>
main(){
int n;
printf("Enter number of elemets in array:\n");
scanf("%d",&n);
int a[n];
int i,j,k,x,l;
for (i=0;i<=n-1;i++)
{
printf("enter element %d:\n",i+1);
scanf("%d",&a[i]);
}
for (j=0;j<=n-1;j++)
{
for (k=j+1;k<=n-1;k++)
{
if (a[j]>a[k])
{
x=a[k];
a[k]=a[j];
a[j]=x;
}
}
}
printf("Maximum Element : %d\n",a[n-1]);
printf("Minimun Element : %d",a[0]);
}
