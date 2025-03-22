### Question 1
```python
# Write a function called 'check_number' that takes a number as parameter.
# The function should return "Positive" if the number is positive,
# "Negative" if the number is negative, and "Zero" if the number is zero.
# Then call the function with a number input by the user.

# Example:
# Input: 5
# Output: Positive

def check_number(num):
    # code here
    pass

num = int(input("Enter a number: "))
result = check_number(num)
print(result)
```

### Question 2
```python
# Write a function called 'calculate_grade' that takes a score (0-100) as parameter.
# The function should return:
# "A" if the score is 90-100
# "B" if the score is 80-89
# "C" if the score is 70-79
# "D" if the score is 60-69
# "F" if the score is below 60
# Then call the function with a score input by the user.

# Example:
# Input: 85
# Output: B

def calculate_grade(score):
    # code here
    pass

score = int(input("Enter your score (0-100): "))
grade = calculate_grade(score)
print(grade)
```

### Question 3
```python
# Write a function called 'check_eligibility' that takes age and citizenship as parameters.
# The function should return "Eligible to vote" if the person is 18 or older and 
# is a citizen, otherwise return "Not eligible to vote".
# Then call the function with user inputs.

# Example:
# Input: 20 yes
# Output: Eligible to vote

def check_eligibility(age, is_citizen):
    # code here
    pass

age = int(input("Enter your age: "))
is_citizen = input("Are you a citizen? (yes/no): ")
result = check_eligibility(age, is_citizen)
print(result)
```

### Question 4
```python
# Write a function called 'calculate_discount' that takes the purchase amount as parameter.
# The function should return the final price after applying the following discounts:
# - If amount is less than 100, no discount
# - If amount is between 100 and 500, 10% discount
# - If amount is more than 500, 20% discount
# Then call the function with an amount input by the user.

# Example:
# Input: 650
# Output: 520.0

def calculate_discount(amount):
    # code here
    pass

amount = float(input("Enter the purchase amount: "))
final_price = calculate_discount(amount)
print(final_price)
```

### Question 5
```python
# Write a function called 'get_season' that takes a month (1-12) as parameter.
# The function should return the season based on the month:
# - Winter: December (12), January (1), February (2)
# - Spring: March (3), April (4), May (5)
# - Summer: June (6), July (7), August (8)
# - Fall: September (9), October (10), November (11)
# Then call the function with a month input by the user.

# Example:
# Input: 7
# Output: Summer

def get_season(month):
    # code here
    pass

month = int(input("Enter a month (1-12): "))
season = get_season(month)
print(season)
```

### Question 6
```python
# Write a function called 'calculate_shipping' that takes the 
# package weight (in kg) and destination ('local' or 'international') as parameters.
# The function should return the shipping cost based on the following rules:
# - Local shipping: $5 for packages under 1kg, $10 for packages 1kg or more
# - International shipping: $15 for packages under 1kg, $25 for packages 1kg or more
# Then call the function with user inputs.

# Example:
# Input: 0.5 local
# Output: 5

def calculate_shipping(weight, destination):
    # code here
    pass

weight = float(input("Enter package weight in kg: "))
destination = input("Enter destination (local/international): ")
cost = calculate_shipping(weight, destination)
print(cost)
```

### Question 7
```python
# Write a function called 'validate_password' that takes a password as parameter.
# The function should return:
# "Strong password" if the password has at least 8 characters and contains a digit
# "Medium password" if the password has at least 8 characters but no digits
# "Weak password" if the password has fewer than 8 characters
# Then call the function with a password input by the user.
# Hint: Use isdigit() method to check if a character is a digit, and any() with a generator.

# Example:
# Input: Pass123
# Output: Strong password

def validate_password(password):
    # code here
    pass

password = input("Enter a password: ")
strength = validate_password(password)
print(strength)
```

### Question 8
```python
# Write a function called 'calculate_bmi' that takes weight (in kg) and height (in meters) as parameters.
# The function should calculate the BMI (weight / height^2) and return a message based on the following:
# - BMI < 18.5: "Underweight"
# - 18.5 <= BMI < 25: "Normal weight"
# - 25 <= BMI < 30: "Overweight"
# - BMI >= 30: "Obesity"
# Then call the function with user inputs.

# Example:
# Input: 70 1.75
# Output: Normal weight

def calculate_bmi(weight, height):
    # code here
    pass

weight = float(input("Enter your weight in kg: "))
height = float(input("Enter your height in meters: "))
category = calculate_bmi(weight, height)
print(category)
```

### Question 9
```python
# Write a function called 'triangle_type' that takes three side lengths as parameters.
# The function should return:
# "Not a triangle" if the sides cannot form a triangle
# "Equilateral" if all sides are equal
# "Isosceles" if exactly two sides are equal
# "Scalene" if no sides are equal
# Note: Sides can form a triangle if the sum of the lengths of any two sides is greater than the length of the remaining side.
# Then call the function with user inputs.

# Example:
# Input: 3 3 3
# Output: Equilateral

def triangle_type(side1, side2, side3):
    # code here
    pass

side1 = float(input("Enter length of first side: "))
side2 = float(input("Enter length of second side: "))
side3 = float(input("Enter length of third side: "))
result = triangle_type(side1, side2, side3)
print(result)
```

### Question 10
```python
# Write a function called 'calculate_taxes' that takes annual income as parameter.
# The function should calculate and return the tax amount based on the following brackets:
# - Income up to $10,000: 0% tax
# - Income $10,001 to $50,000: 10% tax on the amount above $10,000
# - Income $50,001 to $100,000: $4,000 + 20% tax on the amount above $50,000
# - Income above $100,000: $14,000 + 30% tax on the amount above $100,000
# Then call the function with an income input by the user.

# Example:
# Input: 75000
# Output: 9000.0

def calculate_taxes(income):
    # code here
    pass

income = float(input("Enter your annual income: $"))
tax_amount = calculate_taxes(income)
print(tax_amount)
```
