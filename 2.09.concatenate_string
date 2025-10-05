#include <stdio.h>
#include <string.h>

int main() {
    char a[400], b[200];
    printf("Enter first string: ");
    fgets(a, sizeof a, stdin); a[strcspn(a,"\n")]=0;
    printf("Enter second string: ");
    fgets(b, sizeof b, stdin); b[strcspn(b,"\n")]=0;
    strcat(a, b);
    printf("After concatenation: %s\n", a);
    return 0;
}
