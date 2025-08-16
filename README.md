
Perform Basic Mathematical Operations
# Task 1: Perform Basic Mathematical Operations

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the secound number: "))


addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

if num2 != 0:
    division = num1 / num2
else:
    division = "Undefined"

print("\n -- Result --")
print(f"Addition: {addition:g}")
print(f"Subtraction: {subtraction:g}")
print(f"Multiplication: {multiplication:g}")
print(f"Devision: {division if isinstance(division, str) else f'{division:g}'}")

