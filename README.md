#include<stdio.h>
void main()
{
    int n,t,i,j,m,c=0,a[10],b[10];
    scanf("%d",&n);
    while(n--)

        scanf("%d",&t);

    for(i=1; i<=t; i++)
    {
        for(j=1; j<=t; j++)
        {
            a[i]=t%a[j];
            if(a[i]!=a[j])
            {
                c++;

                break;

            }
        }
    }
printf("%d\n",c);
}

