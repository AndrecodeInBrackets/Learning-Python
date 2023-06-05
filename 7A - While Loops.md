# Lesson 7 - Loops - Part 1 - While Loops
In this lesson, we will learn about loops. More exactly, `while` loops!

# What's a while loop?
The `while` loop is a function in Python that repeats a block of code for the time that you ask it to repeat. 
### Example
```python
num = 0
while num < 10:
  print(num)
  num += 1
```
So. This code will repeat itself until `num` is less than 10. `num` will continue growing, with the help of `num += 1`. The while loop will stop after `num` reaches 10.
```python
num = 0
while num < 10:
  print(num)
  num += 1
print("The program finished!")
```
With the help of *indentation*, the code will print `The program finished!` after the `while` loop will stop.

> NOTE: If you don't do something that can stop the loop, there will be NO ESCAPE. That will become an infinite loop.  

# Break
`break` is a keyword that stops the while loop and continues the rest of the code.
``` python
num = 0

while num < 14:
  print(num)
  num += 1
  if num == 5:
    break
print("The program finished")
```

## Good Job!!
You finished this lesson!
```python
exp = 0
while exp <= 7:
  print(exp)
  num += 1
```
