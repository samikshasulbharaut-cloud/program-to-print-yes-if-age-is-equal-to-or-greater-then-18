#a spam comment is defined as atext containing following keywords 
#"make a lot of money","buy now","Subscribe ", "click this",Write a program to detect these spams
m1="Buy now"
m2="click this"
m3="Subscribe"
m4="Make a lot of money"
message=(input("Enter your message: "))
if((m1 in message )or (m2 in message) or (m3 in message) or (m4 in message)):
    print("You are spam")
else:
    print("you are not spam")    
