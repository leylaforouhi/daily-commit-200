def build_multiplication_table(number, limit):
    return [number * value for value in range(1, limit + 1)]


if __name__ == "__main__":
    number = 8
    limit = 10

    table = build_multiplication_table(number, limit)

    print(f"Multiplication table for {number}:")
    for index, result in enumerate(table, start=1):
        print(f"{number} x {index} = {result}")
