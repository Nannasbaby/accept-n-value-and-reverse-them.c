
#include <stdio.h>

int main()
{
    int n;
    scanf("%d",&n);
    int rev=0;
    while(n>0)
    {
        int dig=n%10;
        rev =rev*10+dig;
        n/=10;
    }
    printf("reverse of a number is:%d",rev);

    return 0;
}
