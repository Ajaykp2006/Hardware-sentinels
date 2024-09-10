#include <stdio.h>
int main()
{
    int a,b;
    int c, sum, diff, mul, div;
    scanf("%d %d" , &a , &b);
    printf("enter your option for the calculation");
    printf("1 for addition\n");
    printf("2 for substraction\n");
    printf("3 for multiplication\n");
    printf("4 for division\n");
    scanf("%d" , &c);

    switch(c)
    {
        case 1:
        sum = a + b;
        printf("%d" , sum);
        break;

        case 2:
        diff = a - b;
        printf("%d" , diff);
        break;

        case 3:
        mul= a*b;
        printf("%d" , mul);
        break;

        case 4:
        div = a/b;
        printf("%d" , div);
        break;


    }
     return 0;
}
