## Control Flow
Order in which lines of code are executed 

# Sequential control flow
Execution of code statements one after another, in the order they appear in the program

# Conditional control flow / control flow
Execution of code statements based on some input

if tomorrow == Saturday:
    set alarm for 7
if tomorrow is Tuesday:
    set alarm for 6

# Boolean Data Type Re-visit
Data type that has two values: True and False. Boolean values are used to control the flow of the program.

is_the_earth_flat = False

# Comparison Operators / Relational Operators
Decide the relationship between the operands. Result of comparison is a boolean value (True/False)

# if, elif, else
Simplest form of AI (you could say that)
'if' checks the condition, if true, the intended blocks get executed, if false, it skips the intended blocks

today = "Tuesday"

if today == "Monday":
    print("Set an alarm for 5AM!")
elif today == "Tuesday":
    print("Set an alarm for 6AM!")
elif today == "Saturday":
    print("Set an alarm for 7AM!")

# pass
Does nothing, just...passes..for now

# Boolean Operators
AND, OR, NOT. Operators need to be boolean as well

age = 20
has_permission = False

if age >= 18:
    if has_permission:
        print("Access Granted.")
    else:
        print("Access Denied.")
else:
    print("Access Denied.")

if age >=18 and has_permission:
    print("Access Granted.")
else:
    print("Access Denied.")

# Ternary Operator
Condense a series of code to one line, where applicable

print("Access Granted") if age >=18 and has_permission else print("Access Denied.")

temperature = 30

if temperature > 30:
    message = "It's hot outside."
else:
    message = "It's not hot outside"

print(message)

message = "It's hot outside" if temperature > 30 else "It's not hot outside"

# Match-case 
Control flow, similar to switch statement in other programming languages

day_number = 3

match day_number:
    case 1:
        day_name = "Monday"
    case 2:
        day_name = "Tuesday"
    case 3:
        day_name = "Wednesday"
    case 4:
        day_name = "Thursday"

print(day_name)

# Activity
Write a Python script that asks the user to input a numerical score and catergorizes it into grades (A, B, C, D, F) based onthe following criteria:

    90-100: A
    80-89: B
    70-79: C
    60-69: D
    <59: F
