#Write a program to find whether given username  contains is less than 10 character or not
name=(input("Enter your username :"))
if(len(name)<10):
    print("you are invalid username, it contain less then 10 characters,",len(name))
else:
    print("Done!")    
