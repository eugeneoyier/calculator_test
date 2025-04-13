# Arithmetic and String Practice

# Ask for user input
name = input("What's your name? ")
age = int(input("How old are you? "))
number1 = float(input("Enter a number: "))
number2 = float(input("Enter another number: "))

# Perform arithmetic operations
sum_result = number1 + number2
difference = number1 - number2
product = number1 * number2
if number2 != 0:
    quotient = number1 / number2
else:
    quotient = "Undefined (division by zero)"

# String manipulation
welcome_message = f"Hello, {name}!"
age_message = f"You are {age} years old."

# Output results
print("\n--- Results ---")
print(welcome_message)
print(age_message)
print(f"{number1} + {number2} = {sum_result}")
print(f"{number1} - {number2} = {difference}")
print(f"{number1} * {number2} = {product}")
print(f"{number1} / {number2} = {quotient}")

# Data type display
print("\n--- Data Types ---")
print("Type of name:", type(name))
print("Type of age:", type(age))
print("Type of number1:", type(number1))
print("Type of quotient:", type(quotient))
