# string-hangling-functions
#include <stdio.h>
#include <string.h>   

 int main() 
{
    char str1[50], str2[50], copyStr[50];
    int cmp, len;
 printf("25331A05E8\n");

    printf("Enter first string: ");
    scanf("%s",str1);

    printf("Enter second string: ");
    scanf("%s",str2);

    // String Length
    len = strlen(str1);
    printf("\nLength of first string = %d", len);

    // String Copy
    strcpy(copyStr, str1);
    printf("\nCopied string = %s", copyStr);

    // String Concatenation
    strcat(str1, str2);
    printf("\nAfter Concatenation = %s", str1);

    // String Comparison
    cmp = strcmp(str1, str2);
    if(cmp == 0)
        printf("\nStrings are equal\n");
    else
        printf("\nStrings are not equal\n");

    return 0;
}
