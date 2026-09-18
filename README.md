Practical No. 1

1.	Python Program to Print Hello World.
Source Code:
print('Hello World')


2.	Python program to do arithmetical operations.
Source Code:
A = 10
B = 5
print("Addition =", A + B)
print("Subtraction =", A - B)
print("Multiplication =", A * B)
print("Division =", A / B)
print("Modulus =", A % B)


3.	Python program to swap two variables.
Source Code:
A = 5
B = 10

print("Before swapping Variables:")
print("A =", A)
print("B =", B)

A, B = B, A

print("After swapping Variables:")
print("A =", A)
print("B =", B)

4.	Python Program to Find the Factorial of a Number.

Source Code:
for i in range(2, num + 2):
    factorial = factorial * i

print("Factorial of", num, "=", factorial)

5.	Python Program to Print the Fibonacci sequence.

Source Code:
N = 20
A = 1
B = 2

print("Fibonacci sequence:")

for i in range(N):
    print(A, end=" ")
    A, B = B, A + B

6.	Python program to print the elements of an array.

Source Code:
arr = [5, 10, 15, 20, 25]

print("Elements of the array:")

for element in arr:
    print(element)


7.	Python program to print the largest element and smallest element in an array.

Source Code:

arr = [150, 250, 50, 400, 100]

largest = max(arr)
smallest = min(arr)

print("Array elements =", arr)
print("Largest element =", largest)
print("Smallest element =", smallest)


8.	Python program to add two matrix using array and function.

Source Code:

def add_matrix(A, B):
    return [[A[i][j] + B[i][j] for j in range(2)] for i in range(2)]

A = [[2, 3], [4, 5]]
B = [[6, 7], [8, 9]]

X = add_matrix(A, B)

print("Result:")
for row in X:
    print(row)

9.	Python Program to concatenate two strings.
Source Code:
str1 = "Kwia S."
str2 = "Williams"

result = str1 + " " + str2

print("String after Concatenation:", result)


10.	Python Programs to perform various operations on Strings using functions.
Source Code:
def string_operations(s):
    print("Original String:", s)
    print("Uppercase:", s.upper())
    print("Lowercase:", s.lower())
    print("Length:", len(s))
    print("Reversed:", s[::-1])

string_operations("Programming")



