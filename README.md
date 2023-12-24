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
Developed by: 
RegisterNumber:  
*/
def gcd():
        a=int(input())
        temp=a
        b=int(input())
        while b:
            a,b=b,a%b
        print(f"GCD of two numbers is: {a}")

```

## Output:

![Screenshot 2023-12-24 194838](https://github.com/nainamohamed09642/GCD-of-two-numbers/assets/151916360/8466f089-525f-4251-a59b-da1c06ec5612)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
