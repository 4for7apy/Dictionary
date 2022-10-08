# Dictionary
def add(num1,num2):
  return(num1+num2)

def substraction(num1,num2):
  return(num1-num2)

def product(num1,num2):
  return(num1*num2)

while True:
  print('1. Addition\n2. Subtraction\n3. Product\n4.To Stop The Calculations')
  choice= int(input("Enter a choice...."))

  if choice ==4:
    break
  num1 = int(input('Enter num1: '))
  num2 = int(input('Enter num2: '))

  if choice == 1:
    print(add(num1,num2))
    break
  elif choice ==2:
    print(substraction(num1,num2))
    break
  elif choice ==3:
    print(product(num1 , num2))
    break
  else:
    print("Wrong Input")
