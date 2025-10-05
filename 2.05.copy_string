#include <stdio.h>
#include <string.h>

int main() {
    char src[200], dest[200];
    printf("Enter source string: ");
    fgets(src, sizeof src, stdin);
    src[strcspn(src, "\n")] = '\0';
    strcpy(dest, src);
    printf("Copied string: %s\n", dest);
    return 0;
}
