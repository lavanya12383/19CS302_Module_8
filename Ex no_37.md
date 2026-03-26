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


Create an array of size n dynamically, and read the values from stdin. Iterate the array calculating the sum of all elements. Print the sum and free the memory where the array is stored. While it is true that you can sum the elements as they are read, without first storing them to an array, but you will not get the experience working with an array. Efficiency will be required later. Input Format The first line contains an integer, n.The next line contains space-separated integers Output Format Print the sum of the integers in the array.

## AIM:
To write a program to print the sum of the integers in the array.

## ALGORITHM:
Start.
Define a variables.
Write a program to print the sum of the integers in the array.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.
## PROGRAM:
```
#include<stdio.h>
int main()
{
int i,n,sum=0,arr[100];
scanf("%d",&n);
{
for(i=0;i<n;i++)
scanf("%d",&arr[i]);
for(i=0;i<n;i++)
sum=sum+arr[i];
i++;
}printf("%d",sum);
}
```
## output:
<img width="1674" height="385" alt="image" src="https://github.com/user-attachments/assets/28f34814-dfdd-4749-a0b2-a57802929fc8" />


## RESULT:
Thus, the program is executed and verified successfully.
