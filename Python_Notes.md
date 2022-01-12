# Python Basics #


---
## Lists vs Tuples
 - Lists 

---
## Dictionaries

### Basics
 - key : value pairs are always enclosed in { }
 - syntax for key : value pairs is {key:value}
 - values can be ANY type (integers, strings, floats, booleans and lists)
 - keys must be immutable objects (integers, strings, floats) BUT CANNOT be a list or other type of mutable/changeable object

### How To Create/Initialize a Dictionary
 - syntax for a blank dictionary
    ```
    my_dictionary = {}
    ```
 - to create a key and value pair in that dictionary
    ```
    my_dictionary["KEY NAME"] = VALUE
    ```
 - to view what exists in the dictionary
    ```
    my_dictionary
    ```
### Other Dictionary Arguments
 - Length of a Dictionary
    ```
    len(my_dictionary)
    ```
 - Get the dictionary and its key : value pairs as a TUPLE (ordered list that is *unchangeable*)
    ```
    my_dictionary.items()
    ```
    *this argument cannot use list indexing*

### Decision Statements

 - a double equals sign == is a comparison operator or Boolean operator which means "equal to"
 - nested if else statements look like:
    ```
    score = int(input("What is the score?"))
    
    if score >= 90:
        print("Your grade is an A")
    else:
        if score >= 80:
            print("Your grade is a B")
        else:
            if score >= 70:
                print("Your grade is a C")
            else:
                if score >= 60:
                    print("Your grade is a D")
                else:
                    print("Your grade is a F")
    ```
- nested else if scores can also use if-elif-else statements (use if you have to scroll right to read all of your code!)
    ```
    score = int(input("What is the score?"))

    if score >= 90:
        print("Your grade is an A")
    elif score >= 80:
        print("Your grade is a B")
    elif score >= 70:
        print("Your grade is a C")
    elif score >= 60:
        print("Your grade is a D")
    else:
        print("Your grade is a F")
    ```
---
 ## Resources
 ### General ###
 - Built-In Function of Python Interpreter (https://docs.python.org/3.7/library/functions.html)
 - Automate the Boring Stuff (https://automatetheboringstuff.com/)
 ### F-Strings ###
 - An Improved Formatting Syntax (https://realpython.com/python-f-strings/)