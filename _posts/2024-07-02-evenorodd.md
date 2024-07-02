---
title: " To find even or odd numbers "
date: 2024-07-02
categories:
---

## Program to find the even or odd numbers

```c
#include<cs50.h>
#include<stdio.h>

int main(void)
{
    printf("To find even or odd\n");
    int n1;
    n1 = get_int("Enter first number\n");
    if (n1%2==0)
      {
        printf("given niumber %i is even\n",n1);
      }
        else
        {
        printf("given number %i is odd\n",n1);
        }
}
```
