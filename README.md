int main(){

 struct ven_machine drinks[3] = {"Item1", "Item2", "Item3"};

    int d;

    int r;

    struct machine sd;

    struct machine pr;

    struct machine py;

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

return 0;
}


