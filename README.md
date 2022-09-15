# c_program.c
// reverse program 

#include <stdio.h>

int main() {
    int n,reverse=0,remainder;
    printf("enter the n value");
    scanf("%d",&n);
    while(n!=0)
    {
        remainder = n%10;
        reverse = reverse*10+remainder;
        n/=10;
    }
    printf("reverse number =%d ", reverse);
    return 0;
}
