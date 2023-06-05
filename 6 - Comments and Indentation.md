# Lesson 6 - Comments and Indentation
# This one's short!

# Comments
Comments in python help programmers know what parts of a code do and don't! They are just aesthetic codeblocks!

# How to Make Comments?
To make a comment in your Python file, use `#` and then put a space (to be readable) and then write everything you want.  
Another thing comments can do is canceling a code line!

```python
# This is a comment!
```
To cancel a code line you just get this chunk of code:

```python
var = "Crazzy"
print("Crazzy")
print(var)
```
And then put a `#` where you don't want code to work anymore but still want to have it:
```python
var = "Crazzy"
#print("Crazzy")
print(var)
```

# Indentation
Indentation is something in Python that allows `if` statements, `else`, `while` and others to work properly.
### Example
```python
if num == 10:
  print("yea")
```
As you can see, the `print` function has a bit of space at the beginning. That is called *Indentation*. To make that, press `space` twice or press `tab`. To indent more stuff, double the presses!
```python
if var == 10:
  if num == "Value":
    print("acc")
```
As you can see, I *nested* an `if` inside another `if`.
 
## Off-Topic - Nesting
Nesting is basically putting an `if` inside another `if`, a `while` inside a `while`(more on `while` loops later), an `if` inside a `while` and so on...
 
## Great!
You finished this lesson!  
```python
exp = 5
exp += 1
print(exp)
```
