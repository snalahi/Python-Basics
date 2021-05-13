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
5. Comparison Operators (==, !=, >, >=, <, <=)
6. not Operator (Logical not)
7. and or Operator (Logical and or)

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
n = input("Please enter your name: ") # input function with a prompt in the assignment
                                      # (implicitly stated).
print("Hello", n)                     # the comma creates a space between Hello and the input

*** Multiple String segments with assigned variables can be placed in a print statement with
comma
print("Hrs =", hours, "Mins =", minutes, "Secs =", seconds) # here hours, minutes and seconds
                                                            # are pre-assigned variables
Output => Hrs = (int) Mins = (int) Secs = (int)             # commas work as space provider
                                                            # (NEWLY FEATURED IN PYTHON3 !!!) 

*** Suppose we have a class called "turtle". Now go through the following code snippet to
get a better understanding on class specific methods (in most cases contructors to create
a new instance or object of the specific class) and object specific methods (which are called
upon on the created object or instance of the class)

import turtle                # imports the turtle module (collection of classes)
screen = turtle.Screen()     # creates the "screen" instance / object with some built-in
                             # features / attributes by the Screen() constructor of the Screen
                             # class
alex = turtle.Turtle()       # creates an instance / object of the Turtle class with the name
                             # "alex" and some built-in features / attributes by the Turtle()
                             # constructor of the Turtle class
alex.forward(150)            ###
alex.left(90)                # bunch of actions on the "alex" object
alex.forward(75)             ###
alex.salary = 500000         # updating attribute / feature / property / primary variable of
                             # the "alex" object

*** In case, you don't need to have the variable associated with an operation, "_" can be
used in place of the variable name
e.g.
for _ in range(3):
  print("Hello World!")

# the above block of code will output three print statements and we omitted the variable
# consideration by "_"
                             
*** Module (collection of classes)
import random               # random is a module
random.random()             # random() is a function inside the random module
random.randrange(1, 7)      # randrange(1, 7) is a function inside the random module

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
Single element tuple should be => (100,) # the comma sends message to the interpreter that,
                                         # we are trying to make a single element tuple
                                         # instead of a parenthesis closed integer

*** Negative indexing
Suppose, a string str = "Python"; Negative indexing will be like below:
                         P    y    t    h    o    n
                        -6   -5   -4   -3   -2   -1
                        
*** Indexing and Slicing
Suppose, L is a list, then indexing will be L[0], L[3], L[5], L[9] etc.
Slicing will be L[0:4]  # items from index 0 to index (4 - 1) = 3
                L[3:7]  # items from index 3 to index (7 - 1) = 6
                L[:5]   # all items from start to index (5 - 1) = 4
                L[5:]   # all items from index 5 to end of the list

*** List item repetition
print([0] * 4) => [0, 0, 0, 0]
print([5, 1] * 5) => [5, 1, 5, 1, 5, 1, 5, 1, 5, 1]
# any list multiplied by an integer i, will produce repetition of the list
# i times

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

*** range() function produces what's called an iterable, something that will generate the
numbers zero through the (integer argument - 1) when we iterate through them in a four loop.
So if I, say for I in range of five it will print out the numbers zero, one, two, three and
four. If I actually want a real list, I would have to cast it. I would take range of five
and pass it to the list function which would turn it into a real list.
### In Runestone Environment:
range(5) => [0, 1, 2, 3, 4]
range(10) => [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

### In actual Python environment implementation:
>>> print(range(5))
range(0, 5)
>>> print(type(range(5)))
<class 'range'>
for i in range(5):
  print(i)
# output
0
1
2
3
4
>>> print(list(range(5)))
[0, 1, 2, 3, 4]

*** for item in items: # Here, item => Iterator Variable
                               items => Iterable

*** An integer is not a sequence and that is why it is uniterable
Iterables are always sequences like lists, strings, tuples etc.

*** Lists are mutable, Strings are immutable

*** List item deletion
a = [1, 2, 3, 4, 5, 6, 7, 8, 9]
del a[1:5]
print(a) => [1, 6, 7, 8, 9]
b = [5, 6, 7, 8]
del b[2]
print(b) => [5, 6, 8]

*** "==" checks whether the objects are equivalent or not (it means even if the objects have
         same structure and content with different ids, the outcome will be True. The objects
         can be completely different while storing in the memory but they are equivalent in
         nature. e.g. a == b is True when a and b are aliases of the same object or they are
         pointing to objects which are equivalent to each other)
         
    "is" checks whether the objects are completely same or not with same id (e.g. a is b will
         be True if a and b are the aliases of a same object in memory with same id and
         content)
         
*** Aliasing and mutable objects (List) can create confusion in code. BE AWARE OF THAT !!!

*** Cloning (Deep Copy)
a = [81, 82, 83]
b = a[:]                 # creates a new list 'b' with all the contents of list 'a'. So, 'b'
                         # is a Deep Copy or Clone of 'a'
print(a == b) => True    # Since 'a' and 'b' are equivalent
print(a is b) => False   # Since 'a' and 'b' are not same (completely different objects in
                         # memory)
b[0] = 5

print(a) => [81, 82, 83]
print(b) => [5, 82, 83]
### DEEP COPY (CLONE) WORKED !!! ###

*** Aliasing is only possible with mutable objects (List) and not possible with immutable
objects (String, Tuples)

*** sort() function re-order the items of a list from smallest to biggest (Ascending Order)

*** pop() function removes the last item from a list and return the value
(A First In First Out - FIFO Queue mechanism)

*** append() function does not create a new object. Just mutate the old object.
append() can be also performed by += operator but UASUALLY DON'T DO THAT !!! THAT CAN BE
REALLY CONFUSING IN SOME CASES.
e.g.
items = [1, 2, 3]
items.append("cat")
print(items) => [1, 2, 3, "cat"]   # same list object just added "cat" at the end of the list
                                   # list mutation
n_items = [1, 2, 3]
n_items = n_items + ["cat"]        # concatenation -> "+" operator
n_items => [1, 2, 3, "cat"]        # completely new list object in memory
                                   # non - mutation (creating a new one)
                                   
*** replace(item1, item2) function => replace item1 by item2

*** Another printing method:
name = "Rodney"
score = -1
print("Hello " + name + ". Your score is " + str(score))
=> Hello Rodney. Your score is -1

*** Print statement with formatter -> format() function
scores = [("Rodney", -1), ("Marlon", 1), ("You", 100)]
for person in scores:
    name = person[0]
    score = person[1]
    print("Hello {}. Your score is {}.".format(name, score))

=> Hello Rodney. Your score is -1.
   Hello Marlon. Your score is 1.
   Hello You. Your score is 100.

*** Decimal point formatting while printing
orig_price = float(input("Enter the price: $"))
discount = float(input("Enter the discount: "))
new_price = (1 - discount / 100) * orig_price
print("${:.2f} discounted by {}% is {:.2f}.".format(orig_price, discount, new_price))

=> inputs: orig_price = $1000, discount = 20
=> output: $1000.00 discounted by 20.0% is 800.00.

If nothing is provided within the {}, then the default places will be printed after the
decimal point.
```
