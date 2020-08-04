#include<stdio.h>
int main()
{
    int input;
    int i;
    int c;
  
   puts("How many times do you want the word \"Hello world\" repated?:");
  
   scanf("%d",&input);
   
   for(i=0;i<input;i++){
    printf("Hello World\n");
   }
   puts( "Are you satisfied?, 1.Yes, 2.No:");
   scanf("%d",&c);
   
   if(c==1){
       printf("Alright! Thank you very much\n");
   }else if(c==2){
       printf("Current updates are been made on the software\n");
   }else{
       printf("Wrong Input\n");
   }

 puts("Thanks for your Feedback\n You can rerun the program, as many times as you want.");
    return 0;
}
