# EX 10 C program to find the factorial of a given number using function without return type without arguments.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function without return type without arguments.

## Algorithm
Start.
Declare the variables.
Prompt the user to enter a value.
Read the value using scanf.
Enter factorial of the number.
End.

## Program:
```
#include <stdio.h>
void mul();
int main()
{
    mul();
}
void mul()
{
    long long int f=1,i,n;
    scanf("%lld",&n);
    for(i=1;i<=n;i++)
    {
     f=f*i; 
    }
    printf("Factorial value is: %lld\n",f);
}
```

## Output:
<img width="1137" height="156" alt="Screenshot 2026-06-08 135649" src="https://github.com/user-attachments/assets/b31e5de2-7911-4fb5-9415-c87909512e19" />


## Result:
Thus the program was executed and the output was verified successfully.
