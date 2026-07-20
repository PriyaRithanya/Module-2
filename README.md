# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16
b=bin(16)
print(b)
```

## Output
<img width="1182" height="272" alt="Screenshot 2026-04-20 141215" src="https://github.com/user-attachments/assets/ac0845b6-110b-4ae0-8d1b-aabb6763f85a" />


## Result
Thus,Python program to convert the number **16** into its **binary representation** using built-in Python functions is executed

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```

## Output
<img width="856" height="445" alt="image" src="https://github.com/user-attachments/assets/cd219c42-a9a8-4aaa-9a00-2ed865c8a581" />

## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
i=int(input())
j=int(input())
z=int(input())
f = lambda a, b,c: a+b+c
print(f(i, j,z))
```
## Output
<img width="778" height="590" alt="image" src="https://github.com/user-attachments/assets/babbceda-1bc2-4a4e-b5e1-603ed2230405" />


## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.
