#include <stdio.h>
#include <string.h>
#include <ctype.h>

int main() {
    char s[200], t[200];
    printf("Enter a string: ");
    fgets(s, sizeof s, stdin);
    s[strcspn(s,"\n")]=0;
    // build cleaned lowercase version (ignore spaces and case)
    size_t j=0;
    for(size_t i=0;i<strlen(s);i++){
        if(!isspace((unsigned char)s[i])) t[j++]=tolower((unsigned char)s[i]);
    }
    t[j]=0;
    int pal = 1;
    for(size_t i=0;i<j/2;i++){
        if(t[i]!=t[j-1-i]) { pal = 0; break; }
    }
    if(pal) printf("Palindrome\n"); else printf("Not a palindrome\n");
    return 0;
}
