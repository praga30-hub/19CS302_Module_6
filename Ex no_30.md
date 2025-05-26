# EX 30 C program to add two integer elements in an array using realloc() and that array already has three elements.

## AIM:
To write a C program to add two integer elements in an array using realloc() and that array already has three elements.

## Algorithm
1. Start.
2. Declare array sizeInitialize array elements using malloc()
3. Update array size usi
4. ng realloc()
5. Print the result.
6. End.
    

## Program:
```
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *arr, size, i;
 size = 3;
 arr = (int *)malloc(size * sizeof(int)); 
 for (i = 0; i < size; i++) {
 arr[i] = i * 10; }
 printf("Original array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }
 printf("\n");
 size *= 2;
 arr = (int *)realloc(arr, size * sizeof(int)); 
 for (i = size / 2; i < size; i++) {
 arr[i] = i * 10;
printf("Updated array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }}
```

## Output:

![image](https://github.com/user-attachments/assets/33e88b23-4bbc-48b5-9b64-27cdef0d6873)


## Result:
Thus the program was executed and the output was verified successfully.
