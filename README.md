# include <stdio.h>
int main() {
    int ch;
    int qn;
    printf("PETROL MANAGEMENT SYSTEM\n");
    printf("refill the petrol\n");
    printf("refill the diesel\n");
    printf("refill the cng\n");
    printf("service the vehicle\n");
    printf("enter choice");
    scanf("%d",&ch);
    switch(ch){
        case 1:printf("refill the petrol\n");
               printf("quantity:");
               scanf("%d",&qn);
               printf("amount:%d",qn*70);
               break;
        case 2:printf("refill the diesel\n");
               printf("quantity: ");
               scanf("%d",&qn);
               printf("amount:%d",qn*90);
               break;
        case 3:printf("refill the cng\n");
               printf("quantity: ");
               scanf("%d",&qn);
               printf("amount:%d",qn*60);
               break;
        case 4:printf("service vehicle\n");
               printf("service amount:%d",30);
               break;
        default:printf("none of above");
               break;
    }
    return 0;
}
