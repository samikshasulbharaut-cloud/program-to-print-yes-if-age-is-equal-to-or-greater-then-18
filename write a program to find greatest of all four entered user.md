#write a program to find greatest of all four entered user
a=int(input("Enter your numbe a: "))
b=int(input("Enter your numbe b: "))
c=int(input("Enter your numbe c: "))
d=int(input("Enter your numbe d: "))
if(a>b and a>c and a>d):
    print("a is greater : ",a)
elif(b>a and b>c and b>d):
    print("b is greater : ",b)
elif(c>a and c>b and c>d):
    print("c is greater : ",c)
elif(d>a and d>b and d>c):
    print("d is greater : ",d)
