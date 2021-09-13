//CHANGE TO UPPER BY CALL BY VALUE
#include<stdio.h>
void touppercase(char *x)
{
    if(*x >='a'&& *x<='z')//if its in lower case.
    *x = *x -('a'-'A'); //MAIN LOGIC:cause "a" ASCII value is larger than 'A'    
}
int main()
{
    char a;
    printf("enter a letter:");
    scanf("%c",&a);
    touppercase(&a);
    printf("%c",a);

}
