# Python-Basics-Python3-Specialization
```
*** Truncated division in python:
(10 // 3) => 3; Wipes out all the decimal points

*** Modulo operator
(10 % 3) => 1; Provides the remainder of the operation

*** Order of operation
1. Parenthesis
2. Exponentiation
3. Multiplication and Division
4. Addition and Subtraction

*** Functions are objects in Python
e.g. print(square) => <function square>

*** Data Type
type() gives us the type of the given value
e.g. type("") => <class 'str'>
type(2) => <class 'int'>
type(3.5) => <class 'float'>

*** String
print('''"Oh, no" she exclaimed, "Ben's bike is broken"''') => "Oh, no" she exclaimed, "Ben's bike is broken" 

*** Variables
message = ""
n = 13
pi = 3.14
THE ABOVE ARE SET VARIABLES

print(message)
print(n)
print(pi)
THE ABOVE ARE REFERENCE VARIABLES

Variable names always start with a letter
"_" is treated as a character in python

*** There is a cool function called input() which takes user input from command line. The function does
not need to be explicitly stated. Whenever the program execution comes accross the input() function in any
form, it stops and ask for user input.

for instance,
n = input("Please enter your name: ") #input function with a prompt in the assignment(implicitly stated)
print("Hello", n) #the comma creates a space between Hello and the input

*** Multiple String segments with assigned variables can be placed in a print statement with comma
print("Hrs =", hours, "Mins =", minutes, "Secs =", seconds) #here hours, minutes and seconds are pre-assigned variables
Output => Hrs = (int) Mins = (int) Secs = (int) #commas work as space provider (NEWLY FEATURED IN PYTHON3 !!!) 

*** Suppose we have a class called "turtle". Now go through the following code snippet to get a better understanding
on class specific methods (in most cases contructors to create a new instance or object of the specific class) and object
specific methods (which are called upon on the created object or instance of the class)

import turtle                #imports the turtle program or library or package
screen = turtle.Screen()     #creates the "screen" instance / object with some built-in features / attributes by the Screen()
                             #constructor of the Screen class
alex = turtle.Turtle()       #creates an instance / object of the Turtle class with the name "alex" and some built-in
                             #features / attributes by the Turtle() constructor of the Turtle class
alex.forward(150)            ###
alex.left(90)                #bunch of actions on the "alex" object
alex.forward(75)             ###
alex.salary = 500000         #updating attribute / feature / property / primary variable of the "alex" object

*** In case, you don't need to have the variable associated with an operation, "_" can be used in place of the variable name
e.g.
for _ in range(3):
  print("Hello World!")
  
The above block of code will output three print statement and we omitted the variable consideration by "_"
                             


```
