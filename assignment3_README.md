###TASK 1######
def factorial(n):
    if n==0 or n==1:
        return 1
    else:
        return n * factorial(n-1)
n=int(input("Enter the value for n:"))
result=factorial(n)
print("The factorial of ",n,"is",result)


####TASK 2####
import math
number=int(input("Enter the number grater then 0 : "))
square_root=math.sqrt(number)
Natural_logarithm=math.log(number)
Sine=math.sin(number)
print("Square root of the ", number,"is",square_root)
print("Natural logarithm of ",number,"is",Natural_logarithm)
print("sine of",number,"is",Sine)
