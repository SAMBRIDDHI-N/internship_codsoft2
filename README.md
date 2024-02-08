# internship_codsoft2
# TASK 3:PASSWORD GENERATOR
# codsoft #internship #python_programming
import random
import string
print("welcome to our random password generator")

length=int(input("Enter the length of password: "))
lowerD=string.ascii_lowercase
upperD=string.ascii_uppercase
digitD=string.digits
symbolsD=string.punctuation
combine=lowerD+upperD+digitD+symbolsD
x=random.sample(combine,length)
password="".join(x)
print(password)
