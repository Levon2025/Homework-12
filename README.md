# Homework-12

#include <stdio.h>

int main (){
  
 int  total_days = 1500;
 int year = 0;
 int month = 0;
 int days_left =0;

 year = total_days/ 365;
 month = total_days/30;
 days_left = total_days %30;
 printf("%d equal to, %dyear,%month,% ddays.left.\n",total_days,year,month,days_left);
 return 0 ;

}
