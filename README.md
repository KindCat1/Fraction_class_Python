# Fraction_class_Python
Python Fraction class. Helps you to work with ordinary fractions (like 2/3), decimal fractions (like 0.1) and integers (like 3)
## Why this library was created?
I created this library because I wanted to make working with fractions easier. Let's look at this code:
```py
print(0.1 + 0.2)
```
If you are not a pro in Python, you will think that the output is `0.3`. But the real output is `0.30000000000000004`. That's because Python can't work with float numbers properly. So, I created a library that will help us in working with it.
## Working with library
My class has:
- GCD and LCM functions
- Fraction class
- Int and DecimalNum functions
### Using GCD and LCM functions
```py
from fraction import GCD, LCM
print(GCD(10, 15))  #5
print(LCM(10, 15))  #30
```
### Using Fraction class
```py
from fraction import Fraction
fr = Fraction(2, 3)  #2/3
fr2 = Fraction(1, 2)  #1/2
print(fr + fr2)  #1 1/6
```
