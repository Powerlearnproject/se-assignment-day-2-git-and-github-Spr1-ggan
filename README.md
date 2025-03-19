print ("Select an operation to perform:")                                                                     
print("1 - Add")
print("2 - Subtract")
print("3 - Multiply")
print("4 - Divide")
Option = (input("choose an operator:"))

if ("option" in ['1','2','3','4',]):
    num1= (input("Enter first number:"))
    num2= (input("Enter second number:"))

    if ("option" =='1'):
         result= num1 + num2
    elif ("option"=='2'):
         result=num1-num2
    elif("option"=='3'):
        result=num1*num2
    elif ("option"=='4'):
        resut= num1/num2

else:
    print("invalid operation entered")

print("The result of the operation is []".format(result))
