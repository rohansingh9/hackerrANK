# hackerrANK
//day 2 operators hackerrank solution challenge ?problem 
#include <stdio.h>
#include <math.h>
#include <string.h>
#include <stdlib.h>

int main()
    {
       int total_cost,round;
       float meal_cost;
       float tip_percent,tip,tax;
       int tax_percent;
       scanf("%f",&meal_cost);
       scanf("%f",&tip); 
       scanf("%f",&tax);  
       //operation
       tip_percent=(meal_cost*tip)/100;
       tax_percent=(tip*tax)/100;
       total_cost=meal_cost+tip_percent+tax_percent+0.5;
    
       printf("%d",(int)total_cost);
       
       
    }
