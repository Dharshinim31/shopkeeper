#include <stdio.h>
    struct storekeeper{
        int rack_No;
        char author[50];
        float price;
    };
    typedef struct storekeeper sk;
int main(){
    int n,i;
    sk a[n];
    scanf("%d",&n);
    for(i=0;i<n;i++){
        scanf("%d",&a[i].rack_No);
        scanf("%s",&a[i].author[50]);
        scanf("%f",&a[i].price);
    }
for(i=0;i<n;i++){
        printf("%d",a[i].rack_No);
        printf("%s",a[i].author);
        printf("%f",a[i].price);
}
    return 0;
}
