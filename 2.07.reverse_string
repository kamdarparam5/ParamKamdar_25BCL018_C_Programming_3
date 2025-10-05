#include <stdio.h>
#include <string.h>

int main() {
    char s[200];
    printf("Enter a string: ");
    fgets(s, sizeof s, stdin);
    s[strcspn(s,"\n")]=0;
    size_t n = strlen(s);
    for(size_t i=0;i<n/2;i++){
        char t = s[i]; s[i]=s[n-1-i]; s[n-1-i]=t;
    }
    printf("Reversed: %s\n", s);
    return 0;
}
