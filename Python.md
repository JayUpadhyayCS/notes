# Python

## Running python program

Save the file with the ending .py  
To run a program with python, you run python (name of program).py
You need to call any functions you use.  
Double quotes are equivalent. 
You dont need a main function if its a simple program without functions. 

## Datatypes
* bool-True or false  
* float- Decimal integer  
* int- Integer  
* str - String  
* complex  
* dict  
* list  
* range  
* set  
* tuple  

## To print something in python
>def main():  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     print("hello,world")  
>if _name_ == "_main_":  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; main()  

Def means define me a function. You do not need to explicitly mention what datatype you are using for the function.

_If name==main is used to start the function._ Need to know more about this   
Python code will not run if you have not indented things properly.   
Usually a colon and then an indent everyline following.   
## Example of a while loop
> while True:  
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; print("hello,world")

True and False need to be capital in python.

## Example for a for loop
>for i in range(50)  
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("hello,world")

## Example of if and if else
>if x < y :  
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("1")  
>elif x > y:  
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("2")  
else:  
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("3")  

Instead of else if, it becomes elif. Notice how : is being used instead of semicolon. 

## Substitue for do while loop
def get_positive_int(prompt)
while True:
n=getint(prompt)
if n>=1:
return n


## Basic python program
>from cs50 import get_string  
>s =get_string("name:")  
>print(f"hello,{s}")  
>print("hello,{}".format(s))

Need to import functions from library using the above syntax.  
There are two ways to implement a string into print shown above. 

## Python Arithmetic

There are two ways to use division. In C it would not be accurate towards decimals as an int, however in python if you use / it will give you proper output. If you wish to use C's divison, // will do that.

'**' Is giving an exponent

## Comments

"""This is a comment"""

## Lists

>book=[]
>1,
>2,
>3

## Class aka struct

>class Student:
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;def__init__(self,name,dorm):
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.name=name
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dorm=dorm
## Python information

len is a function used to find out length of a string.  
sys needs to be imported to use argc(count amount of words in commandline) and argv(which word is being used) 

