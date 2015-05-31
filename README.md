# Python_Syntax
#Variable and Data Types

#This repository includes very basic information for those interested in learning Python.
#Type print "Welcome to Python!" in the code editor and the following text: print "Welcome to Python!" will appear in the interpreter.
print "Welcome to Python!"
print "Welcome to Python!"
#Include comments by utilizing the pound sign at the beginning of the line. Comments make your program easier to understand.
#Multi-line comments 
#Interpreter: the window that runs your Python code line by line and checks for errors
#variable: stores a piece of data and gives it a specific name
#boolean: like a light switch, it can only have two values (true or false)


#Whitespace and Statements

#IndentationError: Python expected an indented block
#Example: (Incorrect)

def spam ()

muffins = 12

return muffins

print spam()

#Example: (Correct)

def spam ()

  muffins = 12

  return muffins

print spam()

#When you need to use a comment that will take several lines you can use """. An example follows:
"""I need to go work out and work on my Java coding class and work on this Python class and my linear algebra class. Oh no, I'm not stressed at all.
"""

Math Operations

addition = 100 + 5

subtraction = 58 - 4

multiplication = 10 * 0.15

division = 81 / 9

#Set a number by exponention

muffins = 10 ** 2

print muffins

#The resulting number will be 100.

#Modulo is a special operator that returns the remainder in a division problem.
#Example:

credits = 5 % 4

print credits

#To compute a percentage, you must first find the decimal value equivalent.
#Example:

#6.75% would equal 0.0675 because 6.75/100 = 0.0675 

#Tip Calculator
#A meal costing $44.50 with tax being 0.0675 and leaving a tip of 15% would make the total bill equal to $54.63. You can calculate this by using the following tip calculator


meal = 44.50
tax = 0.0675
tip = 0.15

meal = meal + meal * tax
total = meal + meal * tip

print("%.2f" % total)






