# EX-NO-6-Pseudo-Random-Number

# AIM

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d\n", random_number);
    }
    return 0;
}
```




# OUTPUT
![image](https://github.com/user-attachments/assets/276845fe-34f3-4bd5-b8d6-1695493339ef)
![image](https://github.com/user-attachments/assets/e6527e59-3c8a-4282-b577-9c02f6a3d054)

# RESULT
Thus Pseudorandom Number Generation Using Standard library has been executed successfully

