#include<stdio.h>
int main()
{
    char a;
    int p,q;
    printf("enter the number");
    scanf("%c",&a);
    {
        scanf("%d%d",&p,&q);
        if(a=='+')
        {
            c=p+q;
            printf("%d",c);
        }
        if(a=='-')
        {
            c=p-q;
            printf("%d",c);
        }
        if(a=='*')
        {
            c=p*q;
            printf("%d",c);
        }
        if(a=='/')
        {
            c=p/q;
            printf("%d",c);
        }
        else
        {
            exit;
        }

    }
}
