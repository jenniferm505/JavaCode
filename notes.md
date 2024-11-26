# SciGuides Notes

## Java101

Println = print in another line

class, public is where it is -->
public class Main {insert code here}

Scope = where a code can actually function
{[j = 2]}
[j cannot function outside of these brackets]

Arrays are lists, states datapoints
-1, 0, 1, 2, 3
-1 is the 0th term
array of size 3 stops at 0, skips all other numbers

/declaring array
type (aka arr) name = [list, list 2, list 3]

new = declare new code/create new
element type ---> the variable, type of var
length = what it's defined as

array of an array = 2d;
array of array of array = 3d array;
    so on... 100d array.
        ---> make sure to tell how much is array
    
    Example:
        [array in the array][array value in specified array]

for = you know how many times you want loop to run, with this perameter
    for everytime you do this, you do that
while = you have no idea, so while ___ lasts
    while we are under this condition, ___ lasts

## Java102

Object = Combines info and actions you do with info; like an irl object (a pen or smth)

Class = holds all the info of what (insert variable) does, what (insert variable) even is
        Static is used for things associated, but it's universal to code within

    public = specific code/object accessible to everyone
    private = specific code/object accessible to only some
        do this when making values!

    final = variable can't be changed later on in code w/ mutations...
        UNLESS variable is not completely altered to smth else, and the object is mutatable

objects are instantly returned with printing:
    System.out.print.ln(command of how it should look when printed)

    toString = convert to a string (the method is above)

### Generics
    Arraylists: array without a fixed length,  easily changeable/addable
        Array 2.0  basically

        name.what you want to do with it
            add = additional value
            get = takes smth
            set = value, what it equals
            size = what is accessible with [name]?
    
        When accessing array lists, make sure to import it with:
            import (whatever, but doc says: java.util.ArrayList)
        
            I assume ArrayList can be changed with the actual name of the Array List?

### subNotes!
/**
* This is how you add comments (javadoc comments)
* Also can use "// insertTextHere"
*/

Add math with:
Math.___

@override = you cancel all previous code for this thing in particular
    Computer sees it as its own thing in the brackets

this.variableName = you're stating that THIS is different to the one specified in the previous/main declared and can alter THIS to do smth a bit different with similar code

### Interfaces: 
    We want to know code is safe for the computer to use for different variables so we can access them
    Defining an interface helps define what said interface can do to existing variables and which
        simply just add "interface" before defining one

    Want to say which variables work for interface?
        use:
            variable "implements" interface
        Classes can work on many different interfaces at once

### Inheritance
    You can now add properties from one class to another w/o rewriting the same code!
        If class B extends (or inherits from) class A, then a B object will also be an example of an A object and can b treated as such.
            use:
                class className "extends" otherClass

    NOT a template for other classes, B can call code/methods from A

protected = you can only call within a class code/inheritors & nowhere else

super = greatest inheritor -- Going back to the first generation instead of second