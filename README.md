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
Developed by: 
RegisterNumber:  
*/
def squareroot(number):
    guess=number/2.0
    while True:
        newguess=0.5*(guess+number/guess)
        if abs(newguess-guess)<1e-10:
            return newguess
        guess=newguess
inputnumber=float(input())
result=squareroot(inputnumber)
print(f"Square root of the number: {result}")
```

## Output:
![image](https://github.com/KishanShreeB/Square-root-of-a-number/assets/144870434/124df9c0-d939-472e-bb28-48b2c85e2866)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
