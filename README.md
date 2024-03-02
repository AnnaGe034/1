# 1# Function to calculate the sum of two numbers
def calculate_sum(num1, num2):
    return num1 + num2

# Main function
def main():
    # Taking input from the user
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    
    # Calculating the sum
    result = calculate_sum(num1, num2)
    
    # Displaying the result
    print("The sum of", num1, "and", num2, "is:", result)

# Calling the main function
if __name__ == "__main__":
    main()
