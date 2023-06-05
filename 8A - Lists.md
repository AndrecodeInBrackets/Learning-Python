# Lesson 8A - Lists
Lists are collections that hold multiple values. For short, lists are the plural of variables.  
Lists are one of the 5 collections in Python. The other ones are:Sets, Tuples and Dictionaries.
Lists are ordered, changeable and allow duplicates.

# How to create a list

To create a list, simply put a name, put an equal, then, in `[]` put the values you want.
```py
fruits = ["apple", "banana", "pineapple"]
```
That's it. This is a list!

# How to actually use a list
To actually use a list in a `print` function write these lines of code:
```py
fruits = ["apple", "banana", "pineapple"]
print(fruits[0])
```
Now you may think:  
— Oh! This code should display `A I R`!  
NO! It doesn't! It actually displays `apple`. This is because every collection starts from `0`.  
`for` loops with the `range` function start with `0` too!
```py
fruits = ["apple", "banana", "pineapple"]

for fruit in fruits:
  print(fruit)
```
This code prints every value from the list.

### To be continued...
