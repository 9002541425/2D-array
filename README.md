#include <stdio.h>
#include<conio.h>
void main()
{
    int array[100][100];
    int n=0,k=0;
    int i,j;
    printf("enter the no. of rows\n");
    scanf("%d",&n);
    printf("enter the no.of columns\n");
    scanf("%d",&k);
    for(i=0;i<n;i++)
       {
        for(j=0;j<k;j++)
     {
         printf("enter value for array[%d][%d]",i,j);
         scanf("%d",&array[i][j]);
    }
    }
    printf("the two dimensional array elements\n");
    for(i=0;i<n;i++)
    {
        for(j=0;j<k;j++)
    {
        printf("%d\t",array[i][j]);
        
        if(j==k-1)
        {
            printf("\n");
        }
    }
    }
}
