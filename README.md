In [2]:
Age=int(input("Enter the age"))
if(Age>18):
  print("Eligible for voting")
else:
  print("Not Eligible for voting")
Enter the age19
Eligible for voting
In [5]:
num=int(input("Enter a number:"))
if(num%2==0):
  print("Even number")
else:
  print("odd number")
Enter a number:9
odd number
In [8]:
num=int(input("enter a number"))
if(num>1):
  for i in range(2,num):
    if(num%i==0):
      print(num,"is not a prime number")
      break
    else:
      print(num,"is a prime number")
enter a number46
46 is not a prime number
In [10]:
num=int(input())
if(num<0):
  print(num,"is negative")
else:
  print(num,"is positive")
1
1 is positive
In [13]:
import math
a = float(input("a: "))
b = float(input("b: "))
c = float(input("c: "))

discriminant = b**2 - 4 * a * c

if discriminant >= 0:
    x_1=(-b+math.sqrt(discriminant))/2*a
    x_2=(-b-math.sqrt(discriminant))/2*a
else:
    x_1= complex((-b/(2*a)),math.sqrt(-discriminant)/(2*a))
    x_2= complex((-b/(2*a)),-math.sqrt(-discriminant)/(2*a))

if discriminant > 0:
    print("The function has two distinct real roots: {} and {}".format(x_1,x_2))
elif discriminant == 0:
    print("The function has one double root: ", x_1)
else:
    print("The function has two complex (conjugate) roots: {}  and {}".format(x_1,x_2))
a: 1.2
b: 2.3
c: 3.4
The function has two complex (conjugate) roots: (-0.9583333333333333+1.3838101587846348j)  and (-0.9583333333333333-1.3838101587846348j)
In [14]:
a=int(input("Enter a number"))
if(a!=0):
  if(a>0):
    print(a,"is a positive number")
  else:
    print(a,"is a negative number")
else:
  print(a,"is zero")
Enter a number0
0 is zero
In [15]:
a=int(input("Enter a number from 1-5"))
if(a!=0):
  if(a==1):
    print("one")
  elif(a==2):
    print("Two")
  elif(a==3):
    print("Three")
  elif(a==4):
    print("Four")
  elif(a==5):
    print("Five")
else:
  print("Invalid Number")
Enter a number from 1-54
Four
In [ ]:

In [21]:
ch = input("Please Enter Your Own Character : ")

if(ch == 'a' or ch == 'e' or ch == 'i' or ch == 'o' or ch == 'u' ):
    print("The Given Character ", ch, "is a Vowel")
else:
    print("The Given Character ", ch, "is a Consonant")
Please Enter Your Own Character : p
The Given Character  p is a Consonant
