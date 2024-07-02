---
title: "Addition of numbers"
date: 2024-07-02
categeries:
---
 

## Program for addition of two numbers 


#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int num1;
    int num2;
    int sum;
    printf("addition of two numbers\n");
    num1 = get_int("first number: ");
    num2 = get_int("second number: ");
    sum = num1 + num2;
    printf("the sum of %i and %i is %i\n", num1, num2, sum);
}
