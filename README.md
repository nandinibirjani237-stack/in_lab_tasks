# in_lab_tasks
# task 1
#include <stdio.h>
int main() {
int item[2][5]={(2,3,4,5,6},{3,2,5,7,8}};
int product, grand_total=0;
for (int j=0;j<5;j++){
int qty = item[o][j];
int price = item[1l[jl;
product = qty*price;
printf(" product %d\n qty %d\n price %din product
%d\n",j+1, qty,price, product):
grand_total += product;
printf("\n") ;
printf("grand total %d"
,grand_total) ;
return 0;
# task 2
#include <stdio.h>
int main() {
for (int i=1; i<7;i++){
for (int j=1;j<i;j++){
if (j%2!=0) ‹
printf("%d ",j*j*j);
}elset
printf("%d ",j*j);
printf("\n");
return 0;

# task 3
#include <stdio.h>
int main() {
for (int i=1;i<6;1++) {
for (int j=1;j<=i;]++){
printf("%d ", i) 
}
printf("\n");
return 0;

# task 4
#include <stdio.h>

int main() {
    for(int i=5;i>=1;i--){
        for(int j=1;j<=i;j++){
            printf("%d ",j);
        }
        printf("\n");
    }
    return 0;
}
# task 5
#include <stdio.h>
int main()
{
    int a[3][3];
    int i, j;
    int square = 1;
    int null = 1;
    int diagonal = 1;
    int upper = 1;
    int lower = 1;
    int identity = 1;
    printf("Enter the elements of a 3x3 matrix:\n");
    for (i = 0; i < 3; i++)
    {
        for (j = 0; j < 3; j++)
        {
            scanf("%d", &a[i][j]);
        }
    }
    for (i = 0; i < 3; i++)
    {
        for (j = 0; j < 3; j++)
        {
            if (a[i][j] != 0)
                null = 0;
            if (i != j && a[i][j] != 0)
                diagonal = 0;
            if (i < j && a[i][j] != 0)
                lower = 0;
            if (i > j && a[i][j] != 0)
                upper = 0;
            if (i == j && a[i][j] != 1)
                identity = 0;

            if (i != j && a[i][j] != 0)
                identity = 0;
        }
    }
    printf("\nMatrix Type Checking:\n");
    if (square)
        printf("Square Matrix: Yes\n");
    if (null)
        printf("Null Matrix: Yes\n");
    else
        printf("Null Matrix: No\n");
    if (diagonal)
        printf("Diagonal Matrix: Yes\n");
    else
        printf("Diagonal Matrix: No\n");
    if (upper)
        printf("Upper Triangular Matrix: Yes\n");
    else
        printf("Upper Triangular Matrix: No\n");

    if (lower)
        printf("Lower Triangular Matrix: Yes\n");
    else
        printf("Lower Triangular Matrix: No\n");

    if (identity)
        printf("Identity Matrix: Yes\n");
    else
        printf("Identity Matrix: No\n");
    return 0;
}
