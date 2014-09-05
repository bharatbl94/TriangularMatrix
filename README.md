TriangularMatrix
================

check whether a matrix is triangular or not.
#include<stdio.h>
int main()
{
	int a,p,i,j,m=0,n=0;
	scanf("%d",&p);
	for(i=1;i<=p;i++)
	{
		for(j=1;j<=p;j++)
		{
			scanf("%d",&a);
			if(j>i&&a!=0)
			{
				m=m+1;
			}
			if(i>j&&a!=0)
			{
				n=n+1;
			}
		}
	}
if(m==0||n==0)
	{
		printf("yes\n");
		
	}
	else
	{
		printf("no\n");
	}
	return 0;
}
