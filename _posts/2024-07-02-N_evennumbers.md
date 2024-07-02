---
title: " To print n even numbers "
date: 2024-07-02
categories:
---

## Program to print n even numbers

```c
#include<cs50.h>
#include<stdio.h>

int main(void)

{
    int n;
    n = get_int("Enter upto which number do you want to print :\n");
    printf("print upto n even numbers\n");

    int num;
    for(num = 0;num <= n;)
    {
        printf(" %i\n ",num);
        num = num+2;
    }
}
```