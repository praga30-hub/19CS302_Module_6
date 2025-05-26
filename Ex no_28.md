# EX 28 C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm
1. Start.
2. Declare enum type
3. Declare all days in a week
4. Print result
5. End
      

## Program:
```
#include <stdio.h>
enum weekdays {
 Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
};
int main() {
 enum weekdays today = Wednesday;
 if (today == Wednesday) {
 printf("Today is Wednesday.\n");
 }
}

```

## Output:

![image](https://github.com/user-attachments/assets/1dd54455-cef4-4ee9-bc83-ff744f86961e)


## Result:
Thus the program was executed and the output was verified successfully.
