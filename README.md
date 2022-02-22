# Python-Programing
# Basic Level - Recursive Function
def addItself(a):
    s=0
    if(a!=1):
        s=a + addItself(a-1)
    return s
num=int(input("Enter Number - " ) )  
print(addItself(num))
    
    
