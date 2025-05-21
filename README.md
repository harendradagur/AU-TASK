Task : Session 1
 Solve these questions own your own and try to test yourself what you have learned in the 
session.

 Happy Learning!
 
 Q1 :- Print the given strings as per stated format.
 Given strings:
 "Data" "Science" "Mentorship" "Program"
 "By" "CampusX"
 
 **Code:-**
 print("Data-" "Science-" "Mentorship-" "Program-" "By-" "CampusX")


 Q2:- Write a program that will convert celsius value to fahrenheit.

**Code:-**

  celsics=float(input("enter temprature in celsius "))
 
  fahrenhite=(celsics*9/5)+32
 
  print(fahrenhite)


 Q3:- Take 2 numbers as input from the user.Write a program to swap 
the numbers without using any special python syntax.

**Code:-**

a=30

b=50

a=a+b

b=a-b

a=a-b

print(a,b)


 Q4:- Write a program to find the euclidean distance between two 
coordinates.Take both the coordinates from the user as input.

**Code:-**

x1=int(input("enter a numbar "))

y1=int(input("enter a numbar "))

x2=int(input("enter a numbar "))

y2=int(input("enter a numbar ")

distance=(x2-x1)**2+(y2-y1)**2

print(distance)


 Q5:- Write a program to find the simple interest when the value of 
principle,rate of interest and time period is provided by the user.

**Code:-**

p=float(input("enter priciple rate "))

i=float(input("enter intrest rate "))

t=float(input("enter time "))

print(p*i*t/100)
 
 Q6:- Write a program that will tell the number of dogs and chicken are 
there when the user will provide the value of total heads and legs.
 For example: Input: heads -> 4 legs -> 12  Output: dogs -> 2 chicken -> 2
 

 Q7:- Write a program to find the sum of squares of first n natural 
numbers where n will be provided by the user.

**Code:-**

n=int(input("enter n number "))

sum_of_square = 0

for i in range(1,1+n):

  sum_of_square+=i**2

print(sum_of_square)


 Q8:- Given the first 2 terms of an Arithmetic Series.Find the Nth term 
of the series. Assume all inputs are provided by the user.

**Code:-**

n1=int(input("enter 1st number "))

n2=int(input("enter 2nd number "))

d=n2-n1

for i in range(5):

  print(n1+i*d)

 Q9:- Given 2 fractions, find the sum of those 2 fractions.Take the 
numerator and denominator values of the fractions from the user.

**Code:-**

n1=int(input("enter 1st numerator "))

d1=int(input("enter 1st denominator "))

n2=int(input("enter 2nd numerator "))

d2=int(input("enter 2nd denominator "))

result=(n1*d2+n2*d1)/(d1*d2)

print(result)


 Q10:- Given the height, width and breadth of a milk tank, you have to 
find out how many glasses of milk can be obtained? Assume all the inputs are provided by the user.
Input: Dimensions of the milk tank H = 20cm, L = 20cm, B = 20cm  Dimensions of the glass h = 
3cm, r = 1cm

**Code:-**

height_of_tank=20

width_of_tank=20

breath_of_tank=20

height_of_glass=3

radius_of_glass=1

volume_tank=(height_of_tank*width_of_tank*breath_of_tank)

volume_glass=(22/7*height_of_glass**2*radius_of_glass)

print(volume_tank//volume_glass)
