# Program to calculate sum of array in C
#include <stdio.h>

int main() {
   int array[10] = {1, 2, 3, 4, 5, 6, 7, 8, 9, 0};
   int sum,i;

   sum = 0;
   
   for(i = 9; i >= 0; i--) {
      sum = sum + array[i];      
   }

   printf("Sum of array is %d.", sum);   

   return 0;
}
