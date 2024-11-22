PRINTING PATTERN:
1111

1111

1111

1111

PREREQUISITE:
Basic knowledge of C language and loops.

ALGORITHM:
Take number of rows/columns as input from the user and save it in any variable (‘r’in this case).
Run a loop ‘r’ number of times to iterate through the rows. From i=0 to i<r.  The loop should be structured as for( i=0 ; i<r ; i++).
Run a nested loop inside the previous loop to iterate through the columns. From  j=0 to j<r. The loop should be structured as for(j=0 ; j<r ; j++).
Inside the nested loop print ‘1’ to print ‘1’ in each column of a row.
Inside the main loop print a newline to move to the next line after a row.
CODE IN C:
#include<stdio.h>
int main()
{
int i,j,r;                                       //declaring integer variables i,j for loops , r for number of rows
printf("Enter the number of rows/columns :\n");  //asking user for number of rows/columns
scanf("%d",&r);                                  //taking input and saving in variable r
for(i=0;i<r;i++)                                 //loop for number of rows
   {
      for(j=0;j<r;j++)                           //loop for number of columns
        {
           printf("1");                          //printing 1
        }
      printf("\n");                              //printing newline
   }
}
TAKING INPUT:
DISPLAYING OUTPUT:
