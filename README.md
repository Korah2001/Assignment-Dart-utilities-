# Assignment-Dart-utilities-
def sum_two_numbers(num1, num2):
    return num1 + num2
for i in range(1, 11):
    print(i)
def switch_case(value):
    switch = {
        "apple": "Fruit",
        "banana": "Fruit",
        "carrot": "Vegetable",
        "potato": "Vegetable"
    }
    return switch.get(value, "Unknown")

# Example usage
print(switch_case("apple"))  # Output: Fruit
print(switch_case("carrot"))  # Output: Vegetable
print(switch_case("orange"))  # Output: Unknown
num = 20
while num >= 10:
    print(num)
    num -= 1
def check_even_odd(num):
    if num % 2 == 0:
        print("Even")
    else:
        print("Odd")

# Example usage
check_even_odd(5)  # Output: Odd
check_even_odd(10)  # Output: Even
def find_largest(numbers):
    return max(numbers)

# Example usage
numbers = [5, 10, 3, 8, 15]
print(find_largest(numbers))  # Output: 15
