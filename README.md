num1 = float(input("enter the first number: "))
num2 = float(input("enter the second nuumber: "))
operation = input("enter the operation(+, -, *, /): ")

#perform the calculation
if operation == "+":
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
    print(f"{5} + {10} ={15}")

    elif operation == "-":
    result = num1 - num2
    print(f"{10} - {5} = {5}")

elif operation == "*":
    result = num1 * num2
    print(f"{10} * {5} = {15}")

elif operation == "/":
    if num2 != 0:
        result = num1 / num2
        print(f"{10} / {5} = {2}")
