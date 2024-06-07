# Control Flow

Order in which lines of code are executed in a program.

Ex: 
print("Hello, welcome to programming with Python")

a = 10
b = 5
result = a + b

print(f"The result of adding {a} and {b} is {result}")
print("Thank you")

# Sequential control flow

Execution of code statements will be one after another, in the order theay appear in the program.

# Conditional control flow / Control flow

Execution of code statements based on some input

if tomorrow is Saturday
    set alarm for 7 am
if tomorrow is Tuesday
    set alarm for 6 am

# Boolean Data Type Re-visit

Data type that has two values: True and False. Boolean values are used to control the flow of the program.

is_the_earth_flat = False
print(is_the_earth_flat)

I_am_happy = True
print(I_am_happy)

# Comparison Operators / Relational Operators
Decide the relationship between the operands. Result of comparison is a boolean value (True / False )
x = 5
y = 7
z = 9

print(x == y)
print(x < z)
print(y >= x)
print(y != z)



if tomorrow == Saturday
    set alarm for 7 am
if tomorrow == Tuesday
    set alarm for 6 am

# if, elif, else
Simplest form of AI (you could say that)
'if' checks the condition, if true, the intended blocks get executed, if false, it skips the intended blocks

today = "Tuesday"

if today == "Monday":
    print("Set an alarm for 5 am!")
if today == "Tuesday":
    print("Set an alarm for 6 am!")
if today == "Saturday":
    print("Set an alarm for 7 am!")

# Pass
Does nothing...it passes...for now

# Boolean Operators
AND, OR, NOT. Operands need to be boolean as well