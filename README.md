# DAY-48
my c langauge pratices 
#include <stdio.h>

 struct student 
 {
     int roll ;
     float mark;
     
 };
 
 int main()
 {
     struct student s1 ;
 
    s1.roll = 65;
    s1.mark = 78.01f;
  
    printf("Roll number=%d\n",s1.roll);
    printf("mark = %2f\n",s1.mark);
  
    return 0;

    
}
