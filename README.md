# Fibonacci-series
#In this repository I did how to to print Fibonacci numbers
n=int(input("enter any number"))
a=0
b=1
print (a)
print (b)
for i in range(2,n):
    c=a+b
    a=b
    b=c
    print (c)
