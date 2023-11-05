# A-simple-programme-on-Array-
A simple programme so that a beginner can understand that how actually "ARRAY WORKS" and also how it's use to print the table , Matrix etc. 
#include<stdio.h>
int main()
{
  
    int marks[2][4] = {{1,2,3,5,},
                       {5,7,8,9}};
    //marks[0] = 34;
   // printf("Marks of student 1 is %d\n",marks[0] = 34);
    //marks[0] = 456;
    //printf("Marks of student 1 is %d\n",marks[0] = 456);
    
    //printf("marks[0]");
    
   // return 0;
   
   //for(int i = 0;i<19;i++)
    // {
       
       // printf("Enter the value of %d elements of the array\n",i);
     // scanf("%d",&marks[i]);
        
      //  }
    
   for(int i = 0;i<2;i++)
     
     {
        
        for(int j = 0;j<4;j++)
        
       {
        
        //printf("The values of %d,%d elements of the array is %d\n",i,j,marks[i][j]);
        
        printf("%d  ",marks[i][j]);
        
        }
        
        printf("\n");
        
     
     }   
          
        return 0;
        
}    
