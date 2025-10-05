#include <stdio.h>
#include <string.h>
#include <ctype.h>

int main() {
    char s[200];
    printf("Enter a string: ");
    fgets(s, sizeof s, stdin);
    s[strcspn(s, "\n")] = '\0';
    for(size_t i=0;i<strlen(s);i++) {
        if(isupper((unsigned char)s[i])) s[i] = tolower((unsigned char)s[i]);
        else if(islower((unsigned char)s[i])) s[i] = toupper((unsigned char)s[i]);
    }
    printf("Toggled: %s\n", s);
    return 0;
}
