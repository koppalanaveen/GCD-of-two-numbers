# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: KOPPALA NAVEEN
RegisterNumber:  212223100023
*/
def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```

## Output:

![image](https://github.com/user-attachments/assets/041b4db4-07f5-482b-b32a-f9d4e90b2e28)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
