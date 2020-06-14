while True:
 print("options:") 
 print("enter 'add' to add two numbers")
 print("enter'substract' to substract two numbers")
 print("enter 'multiply' to multiply two numbers")
 print("enter 'divide' to divide two numbers")
 print("enter 'quit' tocend the programm")
 user_input=(":")
 
 if user_input == "quit":
  break 
 elif user_input == "add":
  num1 = float(input("Enter number:"))
  num2 = float(input("Enter another number:"))
  result = str(num1 + num2)
  print("The answer is" + result)
  
  ...
 elif user_input == "substract":
  num1 = float(input("enter number:"))
  num2 = float(input("enter another number:"))
  result= str(num1 - num2)
  print("The answer is" +result)
   
  ...
 elif user_input == "multiply":
  num1 = float(input("enter number:"))
  num2 = float(input("enter another number"))
  result = (num1 * num2)
  print("The answer is" + result)
  
  ...
 elif user_input == "divide":
  num1 = float(input("enter number"))  
  num2 = float(input("enter another number"))
  result(num1/num2)
  print("The answer is" + result)
  ...
 else:
  print("unkown input")
