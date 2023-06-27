# My-calculator
a calculator that I've made

number1 = int(input("What is the first number?"))
number2 = int(input("What is the second number?"))
operator = input("What is the operator?")
if(operator == "+"):
    result = number1 + number2
elif(operator == "-"):
    result = number1 - number2
elif(operator == "*"):
    result = number1 * number2
elif(operator == "/"):
    if(number2 == 0):
        print("You cannot divide by zero")
    else:
        result = number1 / number2
else:
    print("Please give a valid operator")

print("The result is: " + str(result))
