# Multiplying-two-matrix

## AIM:
To write a program to perform Multiplying-two-matrix using python programming.

## ALGORITHM:
### Step 1:
Import Numpy module as np.
### Step 2:
Get input from the user.
### Step 3:
Create empty lists l1 and l2.
### Step 4:
Use for loop to append the values into the list created.
### Step 5:
Print the product of two arrays.
## PROGRAM: 
```
To write a python program for multiplying two matrix.
Developed by: Evangelin.S
Register no: 212221230025
import numpy as np
x = int(input())
l1 =[]
l2 =[]
for i in range(x):
    l1.append(int(input()))
for i in range(x):
    l2.append(int(input()))
arr1 = np.array(l1)
arr2 = np.array(l2)
print("Product of two arrays is:",arr1*arr2)
```
## OUTPUT:
![multiplying two array](https://user-images.githubusercontent.com/94219798/153697534-5bb492ce-2cf1-4582-b5db-3ecb518dbe10.JPG)


## RESULT:
Thus the program is written to perform Multiplying-two-matrix using python programming.
