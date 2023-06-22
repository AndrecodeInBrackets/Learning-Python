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
## Indexing
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

## Negative Indexing
```py
fruits = ["apple", "banana",  "orange", "pineapple"]
print(fruits[-1])
```
What I did here is called *Negative Indexing*. This means that the code will start from the end of the list (It sends `pineapple`). If we would put `-2` instead of `-1`, then it would print `orange`.

## Range of Indexes
You can print surtain items from a list like this:
```py
fruits = ["apple", "banana", "orange", "cherry", "kiwi", "melon", "mango", "pineapple"]
print(fruits[2:5])
```
This code will print `orange`, `cherry`, `kiwi` and `melon`.

> NOTE: Do not forget that computers always start counting from `0` and not `1`  

```py
fruits = ["apple", "banana", "orange", "cherry", "kiwi", "melon", "mango", "pineapple"]
print(fruits[:5])
```
If you leave the first value blank, the program would print from the start (`apple`) to the last value (`melon`)

```py
fruits = ["apple", "banana", "orange", "cherry", "kiwi", "melon", "mango", "pineapple"]
print(fruits[3:])
```
If you leave the last one blank, it would print from item `3` (`cherry`) to the end of the list (`pineapple`)

> NOTE: You can do this with Negative Indexing too!

## Great
You finished this lesson!


