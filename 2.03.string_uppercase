#include <stdio.h>
#include <string.h>
#include <ctype.h>

int main() {
    char s[200];
    printf("Enter a string: ");
    fgets(s, sizeof s, stdin);
    s[strcspn(s, "\n")] = '\0';
    for(size_t i=0;i<strlen(s);i++) s[i] = toupper((unsigned char)s[i]);
    printf("Uppercase: %s\n", s);
    return 0;
}
