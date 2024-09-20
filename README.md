
### question 1
```python
# Write a program that asks the user to input their age.
# If the age is 18 or older, print "You are eligible to vote."
# Otherwise, print "You are not eligible to vote."

# Example:
# Input: 20
# Output: You are eligible to vote.

age = int(input("Enter your age: "))
# code here
```

### question 2
```python
# Write a program that takes an integer input from the user
# and checks if it is even or odd. Print "Even" if the number is
# even, otherwise print "Odd".
# Hint: if num % 2 == 0:

# Example:
# Input: 7
# Output: Odd

num = int(input("Enter a number: "))
# code here
```

### question 3
```python
# Write a program that takes two integers as input, a start and an end.
# Use a for-loop to sum all the numbers from start to end (inclusive),
# and print the result.
# Hint: for i in range(start, end + 1):

# Example:
# Input: 1 5
# Output: Sum: 15

start = int(input("Enter start number: "))
end = int(input("Enter end number: "))
total = 0
# code here
```

### question 4
```python
# Write a program that asks the user for 5 integers, one by one, 
# and finds the largest number among them using a for-loop.
# Hint: if max_num is None or num > max_num:

# Example:
# Input: 3 8 12 5 7
# Output: The maximum number is: 12

max_num = None
for i in range(5):
    num = int(input(f"Enter number {i+1}: "))
    # code here
```

### question 5
```python
# Write a program that takes an integer input from the user and prints
# the multiplication table for that number from 1 to 10 using a for-loop.
# Hint: {num} x {i} = {num * i}

# Example:
# Input: 3
# Output:
# 3 x 1 = 3
# 3 x 2 = 6
# ...
# 3 x 10 = 30

num = int(input("Enter a number: "))
# code here
```

### question 6
```python
# Write a program that takes an integer input from the user
# and prints the sum of all even numbers between 1 and that number (inclusive).
# If the input is less than 2, print "No even numbers to sum."
# Hint: Use a for-loop and an if-statement to check for even numbers.

# Example 1:
# Input: 10
# Output: Sum of even numbers: 30

# Example 2:
# Input: 1
# Output: No even numbers to sum.

num = int(input("Enter a number: "))
# code here
```

### question 7
```python
# Write a program that asks the user to input a word.
# Then, use a for-loop to print each character of the word on a new line.
# Hint: You can loop over a string character by character using a for-loop.

# Example:
# Input: hello
# Output:
# h
# e
# l
# l
# o

word = input("Enter a word: ")
# code here
```

### question 8
```python
# Write a program that takes an integer input from the user
# and prints "Prime" if the number is a prime number, otherwise print "Not Prime."
# Hint: A prime number is only divisible by 1 and itself. Use a for-loop to check divisibility.

# Example 1:
# Input: 7
# Output: Prime

# Example 2:
# Input: 10
# Output: Not Prime

num = int(input("Enter a number: "))
# code here
```

### question 9
```python
def is_prime(n):
    # Numbers less than or equal to 1 are not prime
    if n <= 1:
        return False
    # Check divisibility from 2 to the square root of n
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True
    
# Write a program that takes an integer input from the user
# and prints "Prime" if the number is a prime number, otherwise print "Not Prime."
# Hint: A prime number is only divisible by 1 and itself. Use a for-loop to check divisibility.

# Example 1:
# Input: 7
# Output: Prime

# Example 2:
# Input: 10
# Output: Not Prime

num = int(input("Enter a number: "))
# code here
```

### question 10
```python
# Write a program that asks the user for a positive integer n.
# Use a for-loop to print the factorial of the number.
# The factorial of a number is the product of all integers from 1 to n (inclusive).
# Hint: Initialize a variable to store the result and multiply it by each number in the loop.

# Example 1:
# Input: 5
# Output: Factorial of 5 is 120

# Example 2:
# Input: 3
# Output: Factorial of 3 is 6

n = int(input("Enter a positive integer: "))
# code here
```
