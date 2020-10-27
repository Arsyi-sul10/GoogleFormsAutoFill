


#include<stdio.h>

int main(){
float uang;
int menu;
float kembalian;
char user;

printf("Total amount of money youve already put :  ", uang);
printf("Name list of beverage: ");
    printf("\n\n");

    printf("1. Item1");                          printf("\t\t\tRp . 5000\n");

    printf("2. Item2");                        printf("\t\t\tRp . 6000\n");

    printf("3. Item3");                   printf("\t\t\tRp . 7000\n");

 printf("Enter your choice: ");

    scanf("%d",&menu);



    switch(menu)  {

    case 1:

         printf("You choose Item1");                  printf("\tRp . 5000\n");

         break;

    case 2:

         printf("You choose Item2");                printf("\tRRp . 6000\n");

         break;

    case 3:

         printf("You choose Item3");           printf("\tRp . 7000\n");

         break;

    default:
        printf("Invalid Input\n");
        break;
    }

 printf("Enter your money: ");

    scanf("%.2f",&uang);

    printf("\n\n");

    if(uang > 0)
        printf("Pembayaran berhasil\n");
    else
        printf("Pembayaran Gagal\n");

    printf("\n\n");

    kembalian = uang - menu;
    printf("Kembalian anda %.2f", kembalian);


}

