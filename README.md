#include <stdio.h>
#include <string.h>
int main()
{
    char str[100];
    char rev[100];
    int i, j, len=0;
    printf(" to the reverse function: ");
    gets(str);
    len = strlen(str);
    printf("The reverse function is: ");
    for(i = len - 1; i >= 0; i--) 
    {
         printf("%c", str[i]);
    }
    return 0;
}
