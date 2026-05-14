import random

# Section 1: Generate and print the full array...
print("Section 1: Integers from 50 to 100")

# Create an empty array
numbers = []

# Using a loop, generate 20 random integers from 50 to 100
for i in range(20):
    numbers.append(random.randint(50, 100))

# Print the full array
print("FULL ARRAY")
print(numbers)

# -=-=-=-=-=-=-=-=-=-=-=-=-

# Section 2: Print the Even Integers...
print("\nSection 2: Even Integers")

# Empty result string
result = ""

print("EVEN INTEGERS")

# FOR EACH loop
for each in numbers:

    # Check if even
    if (each % 2) == 0:
        result = result + str(each) + " - "

# Print result
print(result)

# -=-=-=-=-=-=-=-=-=-=-=-=-

# Section 3: Print the Multiples of 5...
print("\nSection 3: Multiples of 5")

# Reset result
result = ""

# FOR EACH loop
for each in numbers:

    # Check if multiple of 5
    if (each % 5) == 0:
        result = result + str(each) + ", "

# Print result
print(result)
