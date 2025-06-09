# python-project
simple calculator  

num1 = int(input("Enter your first number: "))
operation = input("Enter operation (+, -, *, /,%): ")
num2 = int(input("Enter your second number: "))

if operation == '+':
     print("Result:", num1 + num2)
elif operation == '-':
     print("Result:", num1 - num2)
elif operation == '*':
     print("Result:", num1 * num2)
elif operation == '/':
     if num2 != 0:
         print("Result:", num1 / num2)
     else:
         print("Cannot divide by zero!")
elif operation == '%':
    if num2 != 0:
        print("Result:", num1 % num2)
    else:
       print("Error: Cannot take modulus with zero!")
else:
    print("Error: Invalid operator.")
