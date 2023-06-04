# Let it get harder!
# Lesson 4 - Functions
You already know about functions like `print` and `input`. But have you heard of *Custom* functions??? If no then let's learn!

# Custom Functions
Functions like these are made using `def`. Roll the example:
```python
def greet():
  print("Hello!")
 
greet()
 ```
 ```
 Output:
 Hello!
 ```
This is a function. `def`, I think, stands for *define*.
 
## Arguments
We already saw what functions are. Now let's make something fun!
```python
def greet(name):
 print("Hello,", name)
  
greet("Andrecode")
```
That `name` inside the `greet` function is called an *Argument*. This helps on making the function more diverse.
> TIP: The short version is `arg` or `args`(plural)  
> NOTE: If there are more than 1 argument, You need to put the values in order, so you don't get `My name is 30` `My age is Mike` 🤣🤣

## Keyword Arguments (kwargs)
Keyword arguments are the same thing as normal arguments but you do this:
```python
def greet(name, age):
 print("Hello,", name)
 print("Your age is", age )
 
greet(name="Mike", age=25)
```
> As you can see, I added `2` arguments instead of `1`. This is how to put multiple arguments.  

Go look at the last line: You can see that I typed `name="Mike"`. This is a kwarg. The Good thing about kwargs is that you can put the values in any order you want:
```python
def greet(name, age):
 print("Hello,", name)
 print("Your age is", age )
 
greet(age=25, name="Mike")
```
As you can see, I put the age first and then the name, even though in the `def` block it's the opposite!

## Good Job!
You finished the first half of the lesson! Check The part 2 of this lesson to continue!
