import numbers
a=float(input("Enter your first number"))
b=float(input("Enter your second number"))

print("The simple calculator")


print("simple calculator:")
print("a. division")
print("b. add")
print("c. subtract")
print("d. multiply")


choice = input("Enter your choice (a/b/c/d): ")

if choice == 'a':
    print("Result:",a/b)

if choice == 'b':
    print("Result:",a+b)

if choice == 'c':
    print("Result:",a-b)

if choice == 'd':
    print("Result:",a*b)

