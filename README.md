# My First GitHub Project

Hi, I am learning how to use GitHub.

## About this project
This is my first repository where I am practicing
- Creating repositories
- Uploading files
- Making commits

## Files included
- README.md

## My Goal
- Build real projects in future



# Simple Calculator Program

print("Simple Calculator")

# Taking input from user
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter choice (1/2/3/4): ")

if choice == '1':
    print("Result:", num1 + num2)

elif choice == '2':
    print("Result:", num1 - num2)

elif choice == '3':
    print("Result:", num1 * num2)

elif choice == '4':
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error! Division by zero")

else:
    print("Invalid input")




## Output

For Example:

Enter first number: 5  
Enter second number: 3  
Select operation: 1  
Result: 8
