# EEL-ACTIVITY-1
#include <stdio.h>

int main() {
    int i;
    printf("Enter the no:");
    scanf("%d",&i);
    if(i==1){
        printf("\n the geyser is on");
    }
    else if(i==0){ 
        printf("\nthe geyser is off");
    }
    else{
        printf("\ninvalid input");
    }

    return 0;
}
