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
Output => Hrs = (int) Mins = (int) Secs = (int) #commas work as space provider

*** Suppose we have a class called "turtle". Now go through the following code snippet to get a better understanding
on class specific methods (in most cases contructors to create a new instance or object of the specific class) and object
specific methods (which are called upon on the created object or instance of the class)

import turtle                #imports the turtle class or program
screen = turtle.Screen()     #creates the "screen" object with some built-in features by the Screen() constructor of the turtle class
alex = turtle.Turtle()       #creates an instance of the turtle class with the name "alex" and some built-in features by the Turtle()
                             #constructor of the turtle class
alex.forward(150)            ###
alex.left(90)                #bunch of actions on the "alex" object
alex.forward(75)             ###
                             
                             
                             


```
