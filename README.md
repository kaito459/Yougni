# Yougni
print("              Yougni Calulator")
while 1 == 1:
  x = input("Nambre 1 : ")
  x = float(x)
  z = input("Process : ")
  y = input("Nambre 2 : ")
  y = float(y)
  if z == "+":
    print("Result : " , x + y)
    print("              ----------------")
  elif z == "-":
    print("Result : " , x - y)
    print("              ----------------")
  elif z == "*":
    print("Result : " , x * y)
    print("              ----------------")
  elif z == "/":
    print("Result : " , x / y)
    print("              ----------------")
  elif z == "**":
    print("Result : " , x ** y)
    print("              ----------------")
  elif z == "//":
    print("Result : " , x // y)
    print("              ----------------")
  elif z == "%":
    print("Result : " , x % y)
    print("              ----------------")
  else:
    print("Error: Invalid operation. Please use one of the following operations: +, -, *, /, **, //, %.")
    print("              ----------------")
  continue
