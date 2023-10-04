# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
# Developed by : SWETHA.S
# Register number : 212222230155
def sqrt(n):
    a=float(n)
    for i in range(100):
        n=0.5 * (n+a/n)
    return n
a=int(input())
print("Square root of the number:",sqrt(a)) 
*/
```

## Output:
![Screenshot 2023-10-04 211152](https://github.com/swethaselvarajm/Square-root-of-a-number/assets/119525603/a558789f-e433-4bdc-8a04-4741e57363e8)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
