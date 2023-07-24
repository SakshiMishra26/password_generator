# password_generator
import random
import string
print("Welcome to our Random Password generator")
def main():
   
    length=int(input("Enter the length of password you want:"))
    lower=string.ascii_lowercase
    upper=string.ascii_uppercase
    digit=string.digits
    symbols=string.punctuation
    combine=lower+upper+digit+symbols
    x=random.sample(combine,length)
    print(x)
    password="".join(x)
    print(password)
    main()
main()
