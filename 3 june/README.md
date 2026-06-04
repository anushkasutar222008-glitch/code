# Factorial using a loop

num = int(input("Enter a number: "))

factorial = 1

if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    for i in range(1, num + 1):
        factorial *= i
    print(f"Factorial of {num} is {factorial}")



 n = int(input("Enter number: "))

temp = n
rev = 0

while n > 0:
    r = n % 10
    rev = rev * 10 + r
    n = n // 10

if temp == rev:
    print("Palindrome")
else:
    print("Not Palindrome")   




n = int(input("Enter number: "))

s = 0
temp = n

while n > 0:
    r = n % 10
    s = s + r**3
    n = n // 10

if temp == s:
    print("Armstrong Number")
else:
    print("Not Armstrong Number")



n = int(input("Enter terms: "))

a = 0
b = 1

for i in range(n):
    print(a)
    c = a + b
    a = b
    b = c
