#include <stdio.h>
#include <string.h>

int main() {
    char s[200];
    printf("Enter a string: ");
    fgets(s, sizeof s, stdin); s[strcspn(s,"\n")]=0;
    for(int i=(int)strlen(s)-1;i>=0;i--) printf("%c\n", s[i]);
    return 0;
}
