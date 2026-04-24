# fibonacci-project
Python Fibonacci Generator
n = int(input("Enter number of terms: "))

a, b = 0, 1

if n <= 0:
    print("Please enter a positive integer")
elif n == 1:
    print(a)
else:
    for i in range(n):
        print(a, end=" ")
        a, b = b, a + b
