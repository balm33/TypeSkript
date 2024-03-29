# TypeSkript
A scripting language that is written in sentences

# Documentation

### Variables
`the variable`

    Used to prompt variable interaction

`the variable NAME is equal to the TYPE VALUE`
    
    Assigns the variable called NAME to the value VALUE
Variable types
> String, Integer, Float, Boolean, Input

`the variable NAME is equal to the input "This is an input: "`

    Prompts the user for an input, which is stored in the given variable

#### Math
`the variable NAME is increased by VALUE`
    
    Increases the variable called NAME by VALUE

Variable types
> Integer, Float

`the variable NAME is decreased by VALUE`
    
    Decreases the variable called NAME by VALUE

Variable types
> Integer, Float

`the variable NAME is multiplied by VALUE`
    
    Multiplies the variable called NAME by VALUE

Variable types
> Integer, Float

`the variable NAME is divided by VALUE`
    
    Divides the variable called NAME by VALUE

Variable types
> Integer, Float

#### Printing
`print the`
    
    Prints to the console
`print the variable NAME`
    
    Prints the value of the variable NAME to the console

`print the string "MESSAGE"`
    
    prints the written string to the console

`print the integer 1234`
    
    prints the written integer to the console

`print the float 53.3`
    
    prints the written float to the console
    
`print the boolean true`
    
    prints the written boolean to the console

#### If/Else Statements
`if the TYPE NAME __ _____ __ the TYPE ____ then`

    Initiates an if statement where two values are being compared

`if the variable VARNAME is equal to the string 'string' then print the string 'Hello World`

    Checks if the variable VARNAME holds the same value as the string 'string'

`else print the integer 4`

    Will run if the if statement on the previous line fails
**Comparisons**
`is equal to`
> Checks if the two hold the same values

`is greater than`
> Checks if the first is greater than the second

`is less than`
> Checks if the first is less than the second

#### Misc
`get`
    
    Prints attributes of a variable to the console

`get the type of the variable NAME`
    
    Prints the type of the variable called `NAME`

`get the time`

    Prints the current time

`get the time DMY`

    Prints the time in any combination of day month and year

`loop`

    Tells the program to loop infinitely

`Stop`

    Ends the program prematurely and/or ends the loop

#### Scripting
`interpret`

    Interprets the subsequent string in the language given

`interpret python "for i in range(2): \n\tprint(i)"`

    Prints the numbers 0 and 1. Escape codes are required in order to keep the code on a single line

**Languages**
> Python