# triangle-of-1
#include<stdio.h>
int main()
{
int i,j,n;
printf("enter a positive integer:");
scanf("%d",&n);
for(i=0;i<n;++i)
{
	for(j=0;j<i;++j)
	{
	printf("1");

	}
printf("1\n");
}
return 0;
}
