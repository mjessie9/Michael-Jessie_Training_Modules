# Michael Jessie Module One

## Answers:

1. Git is the free and open source distributed version control system that's responsible for everything GitHub
related that happens locally on your computer.
2. git branch "name of branch"
3. Retrieve an entire repository from a hosted location via URL
4. First, you edit your files in the working directory. When you're ready to save a copy of the current state of the project, you stage changes with git add . After you're happy with the staged snapshot, you commit it to the project history with git commit.
5. When you make a change to the main branch you can create a new branch for the commit to be reviewed by someone else to see if it should be pushed to the main branch.


![Smiling Faces](https://images.pexels.com/photos/207983/pexels-photo-207983.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)


[Taylor Swift](https://www.youtube.com/watch?v=b1kbLwvqugk)





# Michael Jessie Module two

## Answers:

1.  pwd
2.  mkdir {dir}
3.  ls
4.  cd ..
5.  cp   example: cp apple another_apple




![Ubuntu Image](https://github.com/mjessie9/Pictures/blob/main/Screenshot_2023-09-29_16_20_53.png)





# Michael Jessie Module Three

## Answers:

1. In Python, you can add a single-line comment by using the # symbol.
2. In C++, you can add a single-line comment by using the // symbols.
3. In Python, you can add a multi-line comment by using triple quotes (''' or """).
4. In C++, you can add a multi-line comment by using the /* and */ symbols.




# Import the built-in Python module for handling keyboard input
import sys

# Define a function to add two numbers
def add_numbers(num1, num2):
    return num1 + num2  # Return the sum of the two numbers

# Define a function to check if a number is odd or even
def check_odd_even(num):
    if num % 2 == 0:  # If the number is divisible by 2 with no remainder
        return "Even"  # The number is even
    else:
        return "Odd"   # The number is odd

# Define the main function that uses the above two functions
def main():
    # Prompt the user to enter the first number
    num1 = int(input("Enter the first number: "))  

    # Prompt the user to enter the second number
    num2 = int(input("Enter the second number: "))  

    sum = add_numbers(num1, num2)  # Add the two numbers

    result = check_odd_even(sum)   # Check if the sum is odd or even

    print(f"The sum of {num1} and {num2} is {sum}, which is an {result} number.")  # Print the result

# Call the main function
if __name__ == "__main__":
    main()
