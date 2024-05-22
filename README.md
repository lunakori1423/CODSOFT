# codsoft calculator
a= float(input("Enter the first digit: "))
b = float(input("Enter the second digit: "))
print("\nChoose an operation given below:")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")
option = int(input("Enter your choice (1/2/3/4): "))
if option==1:
    result=a+b
elif option==2:
    result=a-b
elif option==3:
    result=a*b
elif option==4:
    if b!=0:
        result=a/b
    else:
        print("invalid input:zero cannot be used as a divisor")
        exit()
else:
    print("error:choose your choice from the given number")
    exit()
print(f"Result: {result:.2f}")
