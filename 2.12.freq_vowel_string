#include <stdio.h>
#include <string.h>
#include <ctype.h>

int main() {
    char s[500];
    int cnt[5] = {0}; // a e i o u
    printf("Enter a string: ");
    fgets(s, sizeof s, stdin); s[strcspn(s,"\n")]=0;
    for(size_t i=0;i<strlen(s);i++){
        char c = tolower((unsigned char)s[i]);
        if(c=='a') cnt[0]++;
        else if(c=='e') cnt[1]++;
        else if(c=='i') cnt[2]++;
        else if(c=='o') cnt[3]++;
        else if(c=='u') cnt[4]++;
    }
    printf("a: %d\ne: %d\ni: %d\no: %d\nu: %d\n", cnt[0], cnt[1], cnt[2], cnt[3], cnt[4]);
    return 0;
}
