# dinamyc
# Dynamic code example

# Ask the user for input
operation = input("Enter an operation (+, -, *, /): ")
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform the operation dynamically
if operation == "+":
    result = num1 + num2
elif operation == "-":
    result = num1 - num2
elif operation == "*":
    result = num1 * num2
elif operation == "/":
    if num2 != 0:  # Check for division by zero
        result = num1 / num2
    else:
        result = "Cannot divide by zero"
else:
    result = "Invalid operation"

# Print the result
print("Result:", result)
