#Write a program to calculate the grades of the students from his marks from the following scheme
'''90-100=>excellent
80-90=>A
70-80=>B
60-70=>C
50-60=>D
<50=>Fail'''

marks=(int(input("enter your marks:")))
if(90<= marks <=100):
    print("your grades is excellent")
elif(80<= marks <=90):
    print("your grades is A")
elif(70<= marks <=80):
    print("your grades is B")
elif(60<= marks <=70):
    print("your grades is C")
elif(50<= marks <=60):
    print("your grades is D")
elif(0<= marks <=50):
    print("your are fail")
