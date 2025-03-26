# --------------------------Task-1.py----------------------------
n=0
n=int(input("Enter A Number: "))
def factorial(n):
 if n<2:
    return 1
 else:
   return n*(factorial(n-1))
 
result=factorial(n)
print("Factorial of ",n,"is: ",result)

# --------------------------Task-2.py----------------------------
import math

num=float(input("Enter A Number: "))
square_root=math.sqrt(num)
log=math.log(num)
sine=math.sin(num)
print("Square Root is: ",square_root)
print("log valu is: ",log)
print("Sine: ",sine)
