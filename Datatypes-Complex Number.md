# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
c = complex(4, 6)   # 4 + 6j
print(c)
```
```
real = int(input("Enter real part: "))
imag = int(input("Enter imaginary part: "))

c = complex(real, imag)
print("Complex number is:", c)
```

## Output
![Output](ad.png)
![Output](ae.png)

## Result
the code is verified.
