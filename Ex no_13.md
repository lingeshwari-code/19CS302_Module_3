# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1.Start the program.

2.Declare a 2D array and variables for rows and columns.

3.Read the number of rows and columns, then input all elements of the array.

4.Traverse the array and check if each element is odd using element % 2 != 0.

5.Print only the odd elements and end the program.  

## Program:
```
/*
Program to read the elements and print only the odd elements in the 2D array.
Developed by: Lingeshwari.D
RegisterNumber:  212223060135
*/
#include <stdio.h>

int main() {
    int arr[10][10], rows, cols, i, j;
    scanf("%d%d", &rows, &cols);

    for(i = 0; i < rows; i++) {
        for(j = 0; j < cols; j++) {
            scanf("%d", &arr[i][j]);
        }
    }

    printf("Odd elements in the array:\n");
    for(i = 0; i < rows; i++) {
        for(j = 0; j < cols; j++) {
            if(arr[i][j] % 2 != 0) {
                printf("%d ", arr[i][j]);
            }
        }
    }
    printf("\n");
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/770995cd-9bc5-4e35-bfa1-431e25a184fa)

## Result:
Thus the program was executed and the output was verified successfully.
