def calculate_sum(a, b):
    return a + b

if __name__ == "__main__":
    num1 = 5
    num2 = 10
    result = calculate_sum(num1, num2)
    print(f"The sum of {num1} and {num2} is: {result}")
    def find_max(lst):
    max_num = lst[0]
    for num in lst:
        if num > max_num:
            max_num = num
    return max_num

if __name__ == "__main__":
    numbers = [3, 8, 1, 6, 10, 4]
    max_number = find_max(numbers)
    print(f"The maximum number in the list {numbers} is: {max_number}")
