#include <stdio.h>
#include <string.h>

int main() {
    char s[200];
    printf("Enter a string: ");
    fgets(s, sizeof s, stdin); s[strcspn(s,"\n")]=0;
    for(size_t i=0;i<strlen(s);i++) printf("%c\n", s[i]);
    return 0;
}
