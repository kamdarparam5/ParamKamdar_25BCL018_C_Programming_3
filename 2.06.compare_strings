#include <stdio.h>
#include <string.h>

int main() {
    char a[200], b[200];
    printf("Enter first string: ");
    fgets(a, sizeof a, stdin); a[strcspn(a,"\n")]=0;
    printf("Enter second string: ");
    fgets(b, sizeof b, stdin); b[strcspn(b,"\n")]=0;
    int cmp = strcmp(a,b);
    if(cmp == 0) printf("Strings are same\n");
    else if(cmp < 0) printf("First string is smaller (lexicographically)\n");
    else printf("First string is greater (lexicographically)\n");
    return 0;
}
