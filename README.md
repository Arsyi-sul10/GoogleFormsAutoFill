#include<stdio.h>
struct ven_machine
{

int select;
int harga;
int menu;
int bayar;
 char display;

};

int main(){

 struct ven_machine drinks[3] = {"Item1", "Item2", "Item3"};

    int d;

    int r;

    struct ven_machine sd;

    struct ven_machine pr;

    struct ven_machine py;

for(d = 0;d < 5; d++){
    printf("%c", drinks[d].display);
    }

    for(r = 0; r < 20; r++){

    printf("Please enter a number\n");

    scanf("%d", &sd.select);

   if (sd.select == 1)
 {
   printf("You selected Item1\n", sd.select);
 }
   if (sd.select == 2)
 {

   printf("You selected Item2\n", sd.select);
 }

   if (sd.select == 3)
 {

   printf("You selected Item3\n", sd.select);
        }
    else{
            printf("Input invalid, Only 3 Items are \n");
        }
    }
return (0);

}
