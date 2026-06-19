#write a program to find out whether a student has passed or failed if it requires a total of 40 and at least 30 in each subject to pass . Assume 3 subject and take marks as an input  from user 
#Subject = English
English=[]
a=int(input("Enter your English marks: "))
if (a>40):
    print ("you are pass in English")
elif(a<30):
    print("you are failed")
else:
    print("Try again")
# Subject = Maths 
Maths=[]
b=int(input("Enter your  Maths marks: "))
if (b>40):
    print ("you are pass in Maths")
elif(b<30):
    print("you are failed")
else:
    print("Try again")
# Subject = Biology
Biology=[]
c=int(input("Enter your  Biology marks: "))
if (c>40):
    print ("you are pass in Biology")
elif(c<30):
    print("you are failed")
else:
    print("Try again")

