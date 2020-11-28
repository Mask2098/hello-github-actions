#include<stdio.h>
int main()
{
    int n,i,a[10],x,j;
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    scanf("%d",&x);
    if(x<a[n-1])
    {
		for(i=0;i<n;i++)
		{
		  if(a[i]<x)
		  { 
		   printf("%d ",a[i]);
		  }
		  else if(a[i]==x)
		  {
			 printf("%d %d ",x,a[i]);i+=1;
		     break;
		  }
		  else
		  {
		        printf("%d ",x);
		        break;
		  }
	    }
	    for(;i<n;i++)
	    printf("%d ",a[i]);
	}
	else
	{
	    for(i=0;i<n;i++)
        printf("%d ",a[i]);
	    printf("%d ",x);
	}
}
