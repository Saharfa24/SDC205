# Get user information
name = input("Enter your name: ")
student_id = input("Enter your Student ID: ")

# Get two whole numbers
num1 = int(input("Enter the first whole number: "))
num2 = int(input("Enter the second whole number: "))

# Perform three calculations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

# Display calculation results with two decimal places
print("\nCalculation Results")
print(f"{num1} + {num2} = {addition:.2f}")
print(f"{num1} - {num2} = {subtraction:.2f}")
print(f"{num1} * {num2} = {multiplication:.2f}")

# Compare the two numbers
print("\nComparison")
if num1 > num2:
    print(f"{num1} is larger than {num2}.")
elif num1 < num2:
    print(f"{num1} is smaller than {num2}.")
else:
    print("Both numbers are equal.")

# Display user information
print("\nUser Information")
print(f"Name: {name}")
print(f"Student ID: {student_id}")
