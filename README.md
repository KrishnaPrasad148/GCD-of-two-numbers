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
Program to find the gcd of two number using function.
Developed by: Krishna Prasad.S
RegisterNumber: 212223230108
```
```
def gcd():
    a = int(input("Enter the first value : "))
    b = int(input("Enter the second value : "))
    while b:
        a,b = b, a%b
    print("GCD of two numbers is:",a)
gcd()
```

## Output:
![Screenshot 2024-04-05 113649](https://github.com/KrishnaPrasad148/GCD-of-two-numbers/assets/147332763/fcf6802e-15c2-48ed-8528-e97fc4d9758d)




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
