#include <stdio.h>
int main() {
    int arr[5], freq[5], i, j, count;
    printf("Enter 5 numbers: ");
    for(i=0;i<5;i++){ scanf("%d",&arr[i]); freq[i]=-1; }
    for(i=0;i<5;i++){
        count=1;
        for(j=i+1;j<5;j++){
            if(arr[i]==arr[j]){ count++; freq[j]=0; }
        }
        if(freq[i]!=0) freq[i]=count;
    }
    for(i=0;i<5;i++)
        if(freq[i]!=0) printf("%d occurs %d times\n", arr[i], freq[i]);
    return 0;
}
