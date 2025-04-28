# Basic-Calculator
``` python
#This is a Basic Calculator used to calculate add,sub,mult,div
#This function adds two number
def addition(n1,n2):
    return n1+n2

#This function subs two number
def subtraction(n1,n2):
    return n1-n2

#This function multiplies two numbers
def multiply(n1,n2):
    return n1*n2

#This function divides two numbers
def division(n1,n2):
    if n2==0:
        return "Error!! zero can't be divide"
    return n1/n2


print("Select operator to proceed")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

#Enter the Choice to perform the calculation
choice = int(input("Enter value(1-4):"))

#Enter the Values
num1=eval(input("Enter the first value:"))
num2=eval(input("Enter the second value:"))

if choice == 1 :
    print("Addition of {} and {} is {}".format(num1,num2,addition(num1,num2)))
elif choice == 2:
    print("Subtraction of {} and {} is {}".format(num1,num2,subtraction(num1,num2)))
elif choice == 3:
    print("Multiplication of {} and {} is {}".format(num1,num2,multiply(num1,num2)))
elif choice == 4:
    print("Division of {} and {} is {}".format(num1,num2,division(num1,num2)))
elif choice == 5:
    print("Exit")
else:
    print("Invlaid input")


```
