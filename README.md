# string-in-LOWER-case-using-loop.c
// C program to make string in LOWER case using loop.
#include <stdio.h>

int main() {
    int i;
    char a[15]="GITHUB";
    
    for(i=0;a[i];++i)
     printf("%c",a[i]+32);
     
    return 0;
}
