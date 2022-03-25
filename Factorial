
# Factorial Program

# Introduction

Factorials (!) are products of every whole number from 1 to n. In other words, take the number and multiply through to 1. 

In this program we are able to find factorial of any number.



## For example

 To find factorial of 5:

 5! = 5 * factorial of (5 - 1!)

    = 5 * facrorial of 4 (4!)

    = 5 * 4 * factorial of 3 (3!)
    
    = 5 * 4 * 3 * factorial of 2 (2!)

    = 5 * 4 * 3 * 2 * factorial of 1 (1!)

    = 5 * 4 * 3 * 2  * 1

    = 120

## Program to find factorial
#include <stdio.h>

// Recursion in C

int factorial (int number)

{

    if(number == 1 || number == 0)

   {

       return 1;

   }

   else 
   
   {

       return(number * factorial(number - 1));

   }

}

int main()

{   
    int num;
    
    printf("Enter the number you want the factorial of\n");
    scanf("%d", &num);
    printf("The factorial of %d is %d", num, factorial(num));

    return 0;
}


