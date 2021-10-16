#include <stdio.h>
#include <stdlib.h>

int main()
{
    int row,column;

    printf("enter the no of row in matrix:");
    scanf("%d",&row);
    printf("enter the no of column in matrix:");
    scanf("%d",&column);
    int mat[row][column];
    int i,j;
    for(i=0;i<row;i++){
        for(j=0;j<column;j++){
            printf("enter element for position mat[%d][%d]",i,j);
            scanf("%d",&mat[i][j]);
        }
    }
    int mat2[row][column];
    int l,m;
    if(row==column){
        for(l=0;l<row;l++){
            for(m=0;m<row;m++){
                mat2[l][m]=mat[m][l];

            }
        }
       }
    for(i=0;i<row;i++){
        for(j=0;j<column;j++){
            printf(" %d ",mat2[i][j]);

        }
        printf("\n");
    }
    int f=0;
    for(i=0;i<row;i++){
        for(j=0;j<column;j++){
            if(mat[i][j]==mat2[i][j])
            f++;
        }
    }

    int com=row*column;
    if(f==com){
        printf("symmetrical matrix");
    }
    else{
        printf("not symmetrical");
    }
    return 0;
}
