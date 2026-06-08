# EX 7 Write a C program to print the given triangular number pattern using loop.
EXAMPLE :
INPUT:
5
OUTPUT :
5
44
333
2222
11111

## AIM:
To write a C Program of the above question
## Algorithm
Start.
Declare the variables i,j,k,n.
Prompt the user to enter a value.
Read the value using scanf.
Enter number of rows and columns.
End. 

## Program:
```
#include<stdio.h>
int main()
{
    int i, j, rows;
    scanf("%d",&rows);
    for(i=rows; i>=1; i--)
    {
        for(j=rows; j>=i; j--)
        {
            printf("%d",i);
        }
        printf("\n");
    }
    return 0;
}
```

## Output:
<img width="1127" height="257" alt="image" src="https://github.com/user-attachments/assets/dc48d627-d336-4701-b09d-fe917d797aa5" />


## Result:
Thus the program was executed and the output was verified successfully.
