# Assignment-1 Problem-1
#Code to convert a base 10 number to base 2
from numpy import zeros

x=(input("Enter a base 10 number: "))
i=1    #variable to advance the binary code
s=0    #represents the binary code of the given number

while x>0:
    y=x%2
    s+=(i*y)
    x/=2
    i*=10
print "The base 2 conversion of your given number is: ",s,
