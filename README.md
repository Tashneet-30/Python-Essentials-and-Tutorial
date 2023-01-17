# Python-Essentials-and-Tutorial
Download the lastest version of Python first...!
Then Let's start with the basic
### DATA TYPES first :
1 Integer : Refers to any number (negative,positive)
For eg: 1,-5,98

2.String : (str) Anything embedded in quotations 
For eg : 'tashneet','school'
Also, if a number is enclosed like this '234' , It Behaves as a String.However, does not matter if quotations are Single or Double

3.Bool : True and False 

4.Float : Decimal Number with a floating Type
For eg : 0.765,9.8765

How to create  a VARIABLE :
type name of a variable and then assign the value : 
For eg : x='tshnt'
And if you wish to print the value :
    print(x)
You can even change the value of x again 

#### Variables names can only contain underscores and english alphabets and cannot start with numbers 
and X and x are not similar in Python

### To get INPUT from the user :
    x = input()
    print(x)
    print("Hey..",Enter your age)
    age = input()
    print("Her Age ",age)

## OPERATORS : +,-,*,/ (to perform mathematical operations and calculations)
For eg;

     a= 8
     b = 9
     print(a+b) etc etc.
### Exponents in Python : **
// --> returns the quotient 
% -->   returns the remainder 

### Decision Statement ::
IF/ELIF/ELSE

     if condition=True:
        do this 
     else:
        do this
   
### NOTE : HERE, INDENTATION SHOULD BE PROPER...!!!

    x= int(input())
    if x>9:
      print("Hey")
    elif x>18:
      print("YOYO")
   else:
      print("Done")
   
   
   
### CHAINED CONDITIONALS ::
adding multiple conditionals 

    if x==y and x+y==5:
     do this 
   
   
and :: both conditions on either side must be true 
Similarly, or keyword :: either of the condition should be true 
 not :: replaces anything i.e. TRUE becomes FALSE and vice versa
 
 ## NESTED IF STATEMENTS :: 
     if condtn:
     if condtn:
     else:
     else:
 
 
## LOOPS ::  (FOR)
    for x in range (0,10,1):         ------>>> (start,stop,step)
    print(x)

will print numbers from 0 to 9 i.e. 0 to n-1


## WHILE::
    while condition == True:
      do this 
break :: comes out of the loop 

For eg:

      loop = True
      while loop:
         print("heyyyyyy")
         loop = False
   
   
### LISTS AND TUPLES:::
Lists is an another data types which is a collection of all data  types 
For eg:

    fruits = ['apple','hey',3]
    print(fruits[1])   
### Indexing always starts from zero 

Hence, Hey will be printed...!!!

Add values to list ::
       
       fruits.append('strawberry') ------> using.append()

Change values in List :::

      fruits[0] = 'blueberry'

## Tuples :: List which cannot be changed 
     fruits = (2,3,'hello')
     
### Iterating list in Loops BY ITEM::
     fruits = ['apples','strawberry','pear','jelly']
     for fruit in fruits:
     print(fruit)
     
Also, 
     
     for x in range(0,3):
        if(fruits[x]=='jelly'):
           print("fruits[x])
        else:
           print("not jelly")

### String Methods ::
.strip() :: Removes all the white spaces froma a string.

     x =input('enter a sen')
     print(x.strip())
     print(len(x))
     print(x.lower())
     print(x.upper())
     print(x.split('.'))
     
 len()    :: Returns the length of a string 
 .lower() :: Returns lowercase 
 .upper() :: Returns uppercase 
 .split() :: Returns a list of string  Here splitting occurs from the delimiter ... By default , delimiter is SPACE 
 
 ## SLICE OPERATOR :: Can be used on strings and lists 
      x = 'I am Tashneet Kaur'
      print(x[start::stop::step]
      print(x[0:4])                 -------> Output will be I am
 
 Insert function : 
 
      fruits[0:0] will insert at the beginning 
      
## Functions in Python : 
       def func_name(parameters) 
       returns something 
For eg :

        def subtraction_of_two(number):
        return number-2;
        
Function call :: 

        subtraction_of_two(argument)
        
## Reading from a TEXT FILE :: 
1. Create a File (.txt)
2.  Add some content for reference 
3.  NOTE :: SAVE YOUR FILE IN SAME DIRECTORY WHERE ALL YOUR PYTHON SCRIPT IS PRESENT 

Name a variable :: 

      file = open('File.txt','r')
      f = file.readines()
      print(f)
      newlist=[]
      for line in f:
         if line[-1] =='\n'
          newlist.append(line[:-1])       ----->goes to last character but does not include the last character 
          else:
          newlist.append(line)
      print(newlist)
      file.close()
          
Or 

      file = open('File.txt','r')
       f = file.readines()
       newlist = []
       for line in f:
          newlist.append(line.strip('\n'))
          print(newlist)

## WRITING TO A TEXT FILE:
1. Create a File 
2. Have something written in the file 
     
       file = open('File.txt','w')
       
       
