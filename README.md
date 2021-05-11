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
print('''"Oh, no" she exclaimed, "Ben's bike is broken"''') => "Oh, no" she exclaimed,
                                                                "Ben's bike is broken" 

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

*** There is a cool function called input() which takes user input from command line.
The function does not need to be explicitly stated. Whenever the program execution comes
accross the input() function in any form, it stops and ask for user input.

for instance,
n = input("Please enter your name: ") #input function with a prompt in the assignment
                                      #(implicitly stated).
print("Hello", n)                     #the comma creates a space between Hello and the input

*** Multiple String segments with assigned variables can be placed in a print statement with
comma
print("Hrs =", hours, "Mins =", minutes, "Secs =", seconds) #here hours, minutes and seconds
                                                            #are pre-assigned variables
Output => Hrs = (int) Mins = (int) Secs = (int)             #commas work as space provider
                                                            #(NEWLY FEATURED IN PYTHON3 !!!) 

*** Suppose we have a class called "turtle". Now go through the following code snippet to
get a better understanding on class specific methods (in most cases contructors to create
a new instance or object of the specific class) and object specific methods (which are called
upon on the created object or instance of the class)

import turtle                #imports the turtle module (collection of classes)
screen = turtle.Screen()     #creates the "screen" instance / object with some built-in
                             #features / attributes by the Screen() constructor of the Screen
                             #class
alex = turtle.Turtle()       #creates an instance / object of the Turtle class with the name
                             #"alex" and some built-in features / attributes by the Turtle()
                             #constructor of the Turtle class
alex.forward(150)            ###
alex.left(90)                #bunch of actions on the "alex" object
alex.forward(75)             ###
alex.salary = 500000         #updating attribute / feature / property / primary variable of
                             #the "alex" object

*** In case, you don't need to have the variable associated with an operation, "_" can be
used in place of the variable name
e.g.
for _ in range(3):
  print("Hello World!")

#the above block of code will output three print statements and we omitted the variable
consideration by "_"
                             
*** Module (collection of classes)
import random               #random is a module
random.random()             #random() is a function inside the random module
random.randrange(1, 7)      #randrange(1, 7) is a function inside the random module

*** Don't want to mention random module everytime you call a function, then do the following:
from rendom import random, randrange
*** Then just call the functions by their names:
random()
randrange(1, 7)

*** EOF => End of File

*** Semantic Error => The output is some erroneous representation of what the program should
actually do. This actually does not create any hindrance to the program execution.

*** Develop program incrementally, write 2 or 3 lines, test it and move forward.

*** Three types of errors: Syntax, Runtime and Semantic Error

*** Use triple quotes (""" """ or ''' ''') for multi-line string
e.g.
m = """ or '''
    This is a
    multi-line
    String!
    """ or '''

*** Tuples are immutable whereas Lists are mutable.
Single element tuple should be => (100,) #the comma sends message to the interpreter that,
                                         #we are trying to make a single element tuple
                                         #instead of a parenthesis closed integer

*** Negative indexing
Suppose, a string str = "Python"; Negative indexing will be like below:
                         P    y    t    h    o    n
                        -6   -5   -4   -3   -2   -1
                        
*** Indexing and Slicing
Suppose, L is a list, then indexing will be L[0], L[3], L[5], L[9] etc.
Slicing will be L[0:4]  #items from index 0 to index (4 - 1) = 3
                L[3:7]  #items from index 3 to index (7 - 1) = 6
                L[:5]   #all items from start to index (5 - 1) = 4
                L[5:]   #all items from index 5 to end of the list

*** List item repetition
print([0] * 4) => [0, 0, 0, 0]
print([5, 1] * 5) => [5, 1, 5, 1, 5, 1, 5, 1, 5, 1]
#any list multiplied by an integer i, will produce repetition of the list
#i times

*** count() function counts the number of apperance of provided argument in a
sequence

*** index() function provides the first position of the given argument in a sequence

*** split() takes a string and split it up in a list of words by the spaces encountered
    
*** Use of join() function
    wds = ["red", "green", "blue"]
    glue = " "
    output = glue.join(wds)
    print (output)
    # prints out => red green blue
    
*** for x in range(4): => x is loop variable



```
