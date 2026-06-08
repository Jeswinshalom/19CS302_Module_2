# EX 9 Write a c program to find the sum of Odd digits using do while loop in a Given range
For example:
Input	Result
10
20
75
20
30
125
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
Start
Read num
Convert num to positive if negative
Initialize sum = 0
do-while loop:
Get last digit
If odd, add to sum
Remove last digit
Repeat until num == 0
Print sum
End
## Program:
```
#include <stdio.h>
int main()
{
    int num,limit;
    int sum=0;
    scanf("%d%d",&num,&limit);
    int i=num;
    do{
        if(i%2==1)
        {
       sum=sum+i;
        }
        i++;
    }
    while(i<=limit);
    printf("%d",sum);
    
    return 0;
}

```

## Output:
<img width="1127" height="248" alt="Screenshot 2026-06-08 140703" src="https://github.com/user-attachments/assets/06d4959b-cd2d-4f63-8bc8-ef7be43456e9" />


## Result:
Thus the program was executed and the output was verified successfully.
