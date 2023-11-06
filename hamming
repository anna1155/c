#include <stdio.h>
#include <stdlib.h>
#include <string.h>
int main() {
    char *str1, *str2;
    int n,h=0;
    printf("Enter size of DNA strand : ");
    scanf("%d",&n);
    str1 = (char*) malloc(n * sizeof(char));
    str2 = (char*) malloc(n * sizeof(char));
    scanf("%s",str1);
    scanf("%s",str2);
    if(strlen(str1) == strlen(str2))
    {
        for(int i=0;i<strlen(str1);i++)
        {
            if(str1[i]!=str2[i])
            {
                h++;
            }
        }
    }
    printf("the hamming distance is : %d\n", h);
    return 0;
}
