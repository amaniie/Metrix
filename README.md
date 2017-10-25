#include <stdio.h>

int main()
{
    int m,n,i,j;
    int a[100][100],b[100][100];

    scanf("%d %d",&m,&n);

        for(i=1;i<=m;i++)
        {
            for(j=1;j<=n;j++)
            {
                scanf("%d",&a[i][j]);
            }
        }

        for(i=1;i<=m;i++)
        {
            for(j=1;j<=n;j++)
            {
                scanf("%d",&b[i][j]);
            }
        }

        for(i=1;i<=m;i++)
        {
            for(j=1;j<=n;j++)
            {
                printf("%d",a[i][j]+b[i][j]);
            }
            printf("\n");
        }


    return 0;

}
