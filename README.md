//increasing-numbers
//utilising loop
#include <stdio.h>



int main(void) {
    
    int i,n;
    printf("enter the number of lines required\n");
    scanf("%d",&n);
    if (n<=0){
        printf("0");
        } else {
            while(n<=5){
                for(i=1; i<=n; i++){
                    printf("%d",i);
                }
            printf("\n");
            n++;    
            }    
        }
	return 0;
}
