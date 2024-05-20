# python- calculator
num1 = int(input("enter your first number: "))
num2 = int(input("enter your second number: "))

task = (input("enter your task : "))

subtract = print(task) or print(num1-num2)

multiply = print(task) or print(num1*num2)

divide = print(task) or print(num1/num2)

division = print(task)  or print(num1//num2)

num1 = int(input("Enter your first number: "))
num2 = int(input("Enter your second number: "))
task = input("Enter your task (+ for addition, - for subtraction, * for multiplication, / for division, // for floor division): ")

if task == '+':
    print(f"Result of {num1} + {num2} = {num1 + num2}")
elif task == '-':
    print(f"Result of {num1} - {num2} = {num1 - num2}")
elif task == '*':
    print(f"Result of {num1} * {num2} = {num1 * num2}")
elif task == '/':
    print(f"Result of {num1} / {num2} = {num1 / num2}")
elif task == '//':
    print(f"Result of {num1} // {num2} = {num1 // num2}")
else:
    print("Invalid task entered. Please enter one of the valid operations: +, -, *, /, //")

 
