# LEARNING PYTHON

### VARIABLES
- In python, there is no need to declare the variable type. A single variable name can store any of the data type.
- e.g. myvar = 1 , myvar = 3.24 , myvar = 'c' , myvar = "hello" .
- '+' operator can be either used to concatenate(in case of string type) or add(in case of int and float type).
- mixed variable type cannot be added.

### LISTS
- Lists are very similar to arrays. They can contain any type of variable, and they can contain as many variables as you wish. Lists can also be iterated over  in a very simple manner
- List is declared in following manner - e.g. mylist = [];
- Listname.append(*val*) method is used to add a value to the end of the list.
- List methods can be accessed from [here](https://www.w3schools.com/python/python_ref_list.asp).

### ARITHEMATIC OPERATIONS
- Just as any other programming languages, the addition, subtraction, multiplication, and division operators can be used with numbers.
- "**" operator is used to raise the power of the first number by the second number.
- Lists can be concatenated using the "+" operator
- String or list can be printed, the desired number of times, by using the "**" operator.

### STRING FORMATTING
- % is used to mark the place to print the desired value type format.
- for eg. 
    1. print("hello!, %s " %str);   //prints the value of str in place of the %s.
    2. *In case u want to print several values at the desired places we use, %(**all other data seperated by comma**)*.
    3. Most of the print format is same as of C- language.

### STRING
- String in python can be considered as a character array starting from index 0.
- All the string methods can be accessed from [here](https://www.w3schools.com/python/python_ref_string.asp).

### CONDITIONAL STATEMENTS IN PYTHON.
- The if-else statement :
    - General syntax follows - if condition : /body/        else : /body/
    - We need not enclose the condition in parentheses.
- The if-elif-else statement :  ----    elif as the name suggests is short of else if.
- *BOOL* value is *True* or *False* in python.
- "is" statement is a comparison statement. Unlike == , is statement matches the instance itself.
- "in" statement checks the presence of a variable in a list.

### LOOPS *THE MOST IMPORTANT PART OF ANY PROGRAMMIN LANGUAGE*
- The *for* loop : 
    - for eg.
        1.  primes = [2, 3, 5, 7]
            for prime in primes:
            print(prime)
            // this code prints the values in the list.
    - *range()* and *xrange()* in for loop provide for iterating over a certain range.
        1.  Prints out the numbers 0,1,2,3,4
            for x in range(5):
            print(x)

        2.  Prints out 3,4,5
            for x in range(3, 6):
            print(x)

        3.  Prints out 3,5,7
            for x in range(3, 8, 2):
            print(x)

- The *while* loop : It works the same as in any other programming language. 
- *"else"* statement can also be used with for and while loops, only when they terminate within them, not with break statement.

### FUNCTIONS IN PYTHON
- *def* keyword is used to define a function.
- We can create an object as a return value or can perform any printing actions.

### CLASSES IN PYTHON
- Object can be called an encapsulated entity of member functions and variables. These objects, instead of being created everytime, can be called as an instanece of class. 
- Class can be defined as the collection of member functions and variables from which instances(objects) can be created. 
- exempler code for better understanding of how to use class
    - code:
        -   // define the Vehicle class
            class Vehicle:
            name = ""
            kind = "car"
            color = ""
            value = 100.00
            def description(self):
            desc_str = "%s is a %s %s worth $%.2f." % (self.name, self.color, self.kind, self.value)
            return desc_str

            //your code goes here
            car1 = Vehicle()
            car1.name = "Fer"
            car1.color = "red"
            car1.kind = "convertible"
            car1.value = 60000.00
            //test code
            print(car1.description())

### DICTIONARIES IN PYTHON
- A dictionary is a data type similar to arrays, but works with keys and values instead of indexes. Each value stored in a dictionary can be accessed using a   key, which is any type of object (a string, a number, a list, etc.) instead of using its index to address it. 
- for eg.
    -   phonebook = {}
        phonebook["John"] = 938477566
        phonebook["Jack"] = 938377264
        phonebook["Jill"] = 947662781
        print(phonebook)


              After these, we need to move on to python libraries - numpy, matlplotlib, pandas etc,.
    For writing this resource, the following website have been used - [pyhton-learn](https://www.learnpython.org/en/Welcome).






