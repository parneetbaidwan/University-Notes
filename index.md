# CS1026 - Lecture 1

## Intro to Programming

### Calculating
Operators:
- +, -, *, /, exponents and parentheses
- Variables are used to save values
- Mathematical operators can be used for variables and numbers (literals)

### Variables
Variables hold values and update over time
Rules for naming:
- Letters, numbers and underscores
- Cannot start with a number
- Use informative names

### Division
- Two types of Division: Division and Integer Division
- Division: Divide normally
    - eg) 12/5 = 2.4
- Integer Division: Decimal part is removed
    - eg) 12//5 = 2
- Related operation: mod (%): Gives you only the remainder numerical
    - eg) 12%5 = 2 --> (5+5+2 = 12)

### Statements and Expressions
- Expression: any combination of literals, variables, and operations
- Statement: a line of code that can be executed
- Assignment Statement: "Variable = Expression"
    - "assign the variable the value of the expression"
    - **Only a variable** on the left hand side
    - Equal sign is the assignment operator

### Saving Code
- Save as a .py file
- Executes all at once

### Algorithms
- Once we start saving code, we are implementing algorithms
- Algorithm: A sequence of steps that accomplish a specific task
    - Finite set of steps, depends on data that we get
    - Always solves the problem
- They aren't specific to a language like Python
- When solving problems, algorthms are written before the code is written

### Operations
- Function calls: trig functions, square root, floor, ceiling, logs
- Math module:
    - Import math
    - To use a function, give name and the information needed
    - Store the result in a variable or use an expression
- Math Operators:
    - math.sin, math.tan, math.cos, math.asin...(radians)
    - math.degrees, math.radians (to convert)
    - math.sqrt
    - math.exp, math.log, math.log10
    - math.pi
- Non-math Operators
    - abs() - calculate the absolute value of a numerical value
    - round() - round a numerical value (to a certain number of decimal points)
- String Operations
    - '+' - concatenation (adding strings together)
    - '*' repition
    - len(x) - gives length of string

### Strings
- Store zero or more characters
- Can be assigned to variables and used in expressions
- Define using single or double quotes(' ', " ")
    - eg) myStr = 'COMPSCI 1026B'

### Types
- Strings and numeric values (ints, floats) are different types
- One variable can hold different types over its lifetime
- Some operations only work for some types

### Extracting information from strings
- Can extract a character from a string
- Use square brackets after the string name and provide position
- Position begins at zero, not one

### String Tools
- myStr.upper() - uppercase version of myStr
- myStr.lower() - lowercase version of myStr
- myStr.replace(oldText, newText) -  create a new version with the replacements

### Special Characters
- \n - newline character
- \t - tab character
- \'' or \' - quote characters
- \\ - backslash character

### User Input
- input()
    - Function returns the input the user types
    - Can specify a prompt (string) as a parameter to the function
    - Typically, store user input in a variable
        - use float() to convert to float
        - use int() to convert to integer
        
### Formatting
- Basic method:
    - `print('I want to show you', var1, 'and', var2)`
- Formatted:
    - `print('I want to show you {} and {}'.format(var1, var2))`
    - {} is where the variable will go
- Can also format decimals
    - {:.2f} will result in 2 decimal places
    - `print('A number: {:.2f}'.format(floatingVar))

### Comments
- Anything written after '#' is a comment
- Ignored within the actual code
- Can also use ''' ''' for long paragraphs of comments


### circleArea.py
- this program computes the area of a circle from its radius
`
userInp = input('Please type in the circle radius: ')
radius = float(userInp)

area = 3.141 * (radius**2) # area formula
print('The area of a circle with the radius {} is {:.2f).'.format(radius,area)) `







