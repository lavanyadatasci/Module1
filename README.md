# Conditional Statements in Python: Even or Odd Checker

## Aim

To write a Python program to check whether the given number is even or odd using `if...else` statements.

## Algorithm

1. Get an input from the user.
2. Convert the input to an integer and store it in variable `a`.
3. Check whether `a % 2 == 0`.
4. If the condition is true, print `"EVEN"`.
5. Otherwise, print `"ODD"`.
6. End the program.

## Program

```python
a = int(input("Enter a number: "))

if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```

## Output

```text
Enter a number: 10
EVEN
```

## Result

Thus, the given Python program successfully checks whether a number is even or odd using an `if...else` statement.

# Ex 1: Datatypes - Boolean Expression Evaluation in Python

## Aim

To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## Algorithm

1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label `"a is"`.
6. Print the value of `b` with the label `"b is"`.
7. Print the value of `c` with the label `"c:"`.
8. Print the value of `d` with the label `"d:"`.

## Program

```python
a = 0 == True
b = False == False
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```

## Output

```text
a is False
b is True
c: 2
d: 9
```

## Result

Thus, the Python program successfully evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

# Datatypes - Character Literal in Python

## Aim

To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## Algorithm

1. Print the character `'T'`.
2. Print the character `'a'`.

## Program

```python
print('T')
print('a')
```

## Output

```text
T
a
```

## Result

Thus, the Python program successfully prints the characters `'T'` and `'a'` using character literals.

# Datatypes - Complex Number Creation in Python

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

```python
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))

x = complex(a, b)

print("Complex number:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```

## Output

```text
Enter the real part: 5
Enter the imaginary part: 3
Complex number: (5+3j)
Real part: 5.0
Imaginary part: 3.0
```

## Result

Thus, the Python program successfully creates a complex number from two integers and displays its real and imaginary parts.

# Datatypes - Read and Print a String in Python

## Aim

To write a Python program to read a string from the user and then print it.

## Algorithm

1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## Program

```python id="x7qk3m"
men_stepped_on_the_moon = input("Enter a string: ")
print(men_stepped_on_the_moon)
```

## Output

```text id="h2n8vc"
Enter a string: Neil Armstrong
Neil Armstrong
```

## Result

Thus, the Python program successfully reads a string from the user and prints it.
