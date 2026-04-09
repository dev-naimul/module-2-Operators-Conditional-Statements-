# Module-2-OPERATORS-CONDITIONAL-STATEMENTS

![alt text](image.png)

![alt text](image-1.png)

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

## 2-1 Arithmatic Operator 
- we have 5 type of arithmatic operator + - x(*) / %

```c
#include <stdio.h>
int main()
{
    int a = 10;
    int b = 20;
    // addition 
    int sum = a + b;
    printf("summation = %d\n", sum);
    // subtraction 
    int sub = a - b;
    printf("subtraction = %d\n", sub);
    // multiplication 
    int mult = a * b;
    printf("multiplication = %d\n", mult);
    return 0;
}
```
- lets take input and do using scanf

```c
#include <stdio.h>
int main()
{
    // int a = 10;
    // int b = 20;
    int a, b;

    scanf("a = %d b = %d", &a, &b);
    // addition
    int sum = a + b;
    printf("summation = %d\n", sum);
    // subtraction
    int sub = a - b;
    printf("subtraction = %d\n", sub);
    // multiplication
    int mult = a * b;
    printf("multiplication = %d\n", mult);
    return 0;
}
```
- we will do division in the same way 

```c
#include <stdio.h>
int main()
{
    // int a = 10;
    // int b = 20;
    int a, b;

    scanf("a = %d b = %d", &a, &b);
    // addition
    int sum = a + b;
    printf("summation = %d\n", sum);
    // subtraction
    int sub = a - b;
    printf("subtraction = %d\n", sub);
    // multiplication
    int mult = a * b;
    printf("multiplication = %d\n", mult);

    int div = a / b;
    printf("division = %d\n", div);
    return 0;
}
```
- if the division is supposed to be float we have to keep one of the value float otherwise it will give floored number and also keep the value in float 

```c
#include <stdio.h>
int main()
{
    // int a = 10;
    // int b = 20;
    int a;
    float b;

    scanf("a = %d b = %f", &a, &b);

    float div = a / b;
    printf("division = %f\n", div);
    printf("division = %.2f\n", div);
    return 0;
}
```

## 2-2 Mod Operator 

```c
#include <stdio.h>
int main()
{
    int a;
    int b;

    scanf("a = %d b = %d", &a, &b);

    int rem = a % b;
    printf("remaining = %d",rem);

    return 0;
}
```

## 2-3 Relational operator 

![alt text](image-6.png)

- relational operator will check and give us true or false

## 2-4 & 5 Logical Operator 

![alt text](image-7.png)

- sits between two relation and gives true or false result 

![alt text](image-8.png)

![alt text](image-9.png)

![alt text](image-10.png)

![alt text](image-11.png)

## 2-6 2-7 2-8 Conditional Statement if else 

```c
#include <stdio.h>
int main()
{
    int tk;

    scanf("tk = %d", &tk);

    if(tk <= 100){
        printf("Tumi Gorib!\n");

    }else{
        printf("Ore Borolok");
    }

    return 0;
}
```
## 2-9 Ladder if else 

```c
#include <stdio.h>
int main()
{
    int tk;

    scanf("tk = %d", &tk);

    if(tk >= 100){
        printf("Ore Borolok");
        

    }else if(tk >=50) {
        printf("Tumi Gorib!\n");
    }
    else{
        printf("Ore Miskin");
    }

    return 0;
}
```

## 2-10 2-11 2-11 Nested If else 

```c
#include <stdio.h>
int main()
{
    int tk;

    scanf("tk = %d", &tk);

    if(tk >= 100){
        printf("Tumi Motamoti Borolok\n");
        
        if(tk > 150){
           printf("Tumi onek borolok"); 
        }

    }else if(tk >=50) {
        printf("Tumi Gorib!\n");
    }
    else{
        printf("Ore Miskin");
    }

    return 0;
}
```
## 2-12 variations of if else 
- regular 
- nested 
- ladder 
