---
title: " To identify positive or negative numbers "
date: 2024-07-02
categories:
---

## Program to identify positive or negative numbers

```c
#include<cs50.h>
#include<stdio.h>

int main(void)

{
    int num;
    printf("To find the positive or negative numbers\n");
    num = get_int("Enter a Number :\n");
    if(num>0)
    {
        printf("The given number %i is positive\n",num);
    }
    else
    {
       printf("The given number %i is Negative\n",num);
    }
}
```