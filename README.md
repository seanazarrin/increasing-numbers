//increasing-numbers
//utilising loop
#include <stdio.h>



int main(void) {
    
    int i,w;
    int n=1;
    printf("enter the number of lines required\n");
    scanf("%d",&w);
    if (w<=0){
        printf("0");
        } else {
            while(n<=w){
                for(i=1; i<=n; i++){
                    printf("%d",i);
                }
            printf("\n");
            n++;    
            }    
        }
	return 0;
}
