# # Hackerrank problem - 2

Your task is to take two numbers of int data type, two numbers of float data type as input and output their sum:

Declare 4 variables: two of type int and two of type float.

Read 2 lines of input from stdin (according to the sequence given in the 'Input Format' section below) and initialize your variables.

Use the + and - operator to perform the following operations:

Print the sum and difference of two int variable on a new line.

Print the sum and difference of two float variable rounded to one decimal place on a new line.

## Input Format

The first line contains two integers.

The second line contains two floating point numbers.

## Constraints 

1 ≤ integer variables ≤ 104

1 ≤ float variables ≤ 104

## Output Format

Print the sum and difference of both integers separated by a space on the first line, and the sum and difference of both float (scaled to 1 decimal place) separated by a space on the second line.

Sample Input 

10 4

4.0 2.0

Sample Output 

14 6

6.0 2.0

Explanation

When we sum the integers 10 and 4, we get the integer 14. When we subtract the second number 4 from the first number 10, we get 6 as their difference.

When we sum the floating-point numbers 4.0 and 2.0, we get 6.0. When we subtract the second number 2.0 from the first number 4.0, we get 2.0 as their difference.



# EX 37 C program to print the sum and difference of both integers separated by a space on the first line, and the sum and difference of both float (scaled to 1 decimal place) separated by a space on the second line.
## DATE:11/05/2025
## AIM:
To write a C program to print the sum and difference of both integers separated by a space on the first line, and the sum and difference of both float (scaled to 1 decimal place) separated by a space on the second line.

## Algorithm
1.Start the program and declare two int and two float variables.

2.Read two integers from the first line and two floats from the second line.

3.Calculate the sum and difference of the integers.

4.Calculate the sum and difference of the float values.

5.Print the integer results and float results rounded to 1 decimal place.

## Program:
```
/*
C program to find the smallest among three numbers using Structure.
Developed by: Kamalesh S
RegisterNumber:  212223060108
*/
#include <stdio.h>

int main()
{
    int a, b;
    float x, y;

    scanf("%d %d", &a, &b);
    scanf("%f %f", &x, &y);

    printf("%d %d\n", a + b, a - b);
    printf("%.1f %.1f\n", x + y, x - y);

    return 0;
}



```

## Output:

![image](https://github.com/user-attachments/assets/4b828d4d-1dd1-4721-8793-f5c61da1d5b2)


## Result:
Thus the program was executed and the output was verified successfully.
