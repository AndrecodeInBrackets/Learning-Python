# Lesson 3 - input()
`input()` is my favorite function in Python because it let's the user interact with the code!  
Let's get to work!

## Using input()
To use `input()`, just type it, and run the code. You can see that you can now write in the console!  
But there's no use if this function is placed in the code like that... Let's see how we can store things with this function:

## Storing values using input
To store values, we need to put the `input` function as a value inside a variable, like this:
```python
var = input()
```
Now we just need to print it! 
```python
var = input()
print(var)
```
Now if we run this and write something, we will see the response! Cool!!  

Output:  
*Input is the best*  
Input is the best

# But wait! There's more...
It's pretty boring to use a simple `input` function. But if you didn't know, you can actually put some text inside the `input` function! Let's have a look on how to do it:
```python
var = input("What is your name?: ")

print("Nice to meet you,", var+"!")
```
> As a bonus I added some things from the last lesson!

```
Output:
What is your name?: Andrecode
Nice to meet you, Andrecode!
```

# BONUS - Let's make a game!
BOUNS LEVEL! Let's make a login screen! But with a twist! Use this line of code to get started:
```python
from getpass import getpass
```
This line of code will allow you to hide the password. `getpass` is a *module* (More on Modules later) that works like `input` but hides the user's input.  
Let's start!
```python
from getpass import getpass

username = input("Username: ")
passw = getpass("Password: ")

print("Hello, @"+username+"!")
print("Your password is: ", passw)
```
Go and try it!

## Good Job!
You finished this lesson! You now gain experience lvl 3!
