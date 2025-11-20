# EX:1
### Name: STEFFI J
### Reg no: 212224220107
# 1a. Conditional Statements in Python: Even or Odd Checker

## Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## Program
```
num = int(input("Enter a number: "))

if num % 2 == 0:
    print(f"{num} is an even number.")
else:
    print(f"{num} is an odd number.")
```

## Output

<img width="647" height="212" alt="image" src="https://github.com/user-attachments/assets/bb8b3ed4-e51e-412e-98b7-c159b0311154" />


## Result

Thus,the Python program to check whether the given number is even or odd using if...else statements is created successfully.



# 1b. Datatypes-Boolean Expression Evaluation in Python

## Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## Program

```

a = (0 == True)

b = (False == False)

c = (True + True)

d = (False + 9)

print("a is", a)

print("b is", b)

print("c:", c)

print("d:", d)

```

## Output

<img width="660" height="208" alt="image" src="https://github.com/user-attachments/assets/e945bde3-eaa3-4955-a416-f1634f593b22" />


## Result

Thus,the PPython program that evaluates and prints the results of boolean and arithmetic expressions involving True and False is created successfully.

# 1c. Datatypes-Character Literal in Python

## Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## Program

```

a='T'
b='a'
print(a)
print(b)

```

## Output

<img width="547" height="186" alt="image" src="https://github.com/user-attachments/assets/73afb499-c94a-4702-9e6b-f33cd4cccf05" />


## Result

Thus,the Python program that prints the characters 'T' and 'a' using character literals is created successfully.


# 1d. Datatypes-Complex Number Creation in Python

## Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## Program

```

a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)

```
## Output

<img width="603" height="207" alt="image" src="https://github.com/user-attachments/assets/798654ae-7ca7-4cd2-abfc-28e67577810c" />


## Result

Thus,the Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts is created successfully.

# 1e. Datatypes-Read and Print a String in Python

## Aim
To write a Python program to read a string from the user and then print it.

## Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## Program

```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)
```

## Output

<img width="627" height="197" alt="image" src="https://github.com/user-attachments/assets/0c5afbab-e451-4c24-b198-f86e472f697c" />


## Result

Thus,the Python program to read a string from the user and then print it is created successfully.
