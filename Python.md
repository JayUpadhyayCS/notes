# Python

## Running python program

Save the file with the ending .py  
To run a program with python, you run python (name of program).py
You need to call any functions you use

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

## Basic python program
>from cs50 import get_string  
>s =get_string("name:")  
>print(f"hello,{s}")  
>print("hello,{}".format(s))

Need to import functions from library using the above syntax.  
There are two ways to implement a string into print shown above. 

## Python Arithmetic

There are two ways to use division. In C it would not be accurate towards decimals as an int, however in python if you use / it will give you proper output. If you wish to use C's divison, // will do that.

