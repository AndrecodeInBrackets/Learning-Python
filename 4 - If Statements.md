# Lesson 4 -  If Statements
In this lesson we will learn about `if` statements.

# Introduction
`if` is another function that allows you to decide how the code should run:
```python
var = "Value"

if var == "Value":
  print("The variable is good!")
```
If we run this, it will say `The variable is good`. Let's change `var`'s value to be `"NotVar"`.  
If you didn't notice, I put `==` and not `=`. This is because `=` defines a variable and `==` checks if 2 things are equal to eachother.

## Else

As you can see, nothing happend... That's because there's no `else`. Let's add that piece of code in:
```python
var = "NotVar"

if var == "Value":
  print("The variable is good!")
else:
  print("The variable is BAD!")
```
Now, The console will print `The variable is BAD!`. Cool!

## Elif
`elif` is a function placed after `if` but before `else`. `elif` is short for _esle if_ and is used when you want to add more statements to the code:
```python
var = "NotVar"

if var == "Value":
  print("The variable is good!")
elif var == "NotVar":
  print("The variable is NOT? a variable??")
else:
  print("The variable is BAD!")  
```
So if `var` is `"Value"`, then it says this.  
If `var` is not equal to `"Value"` but to `"NotVar"`, then it says this other thing.  
But if `var` is not equal to both, then it says that.

# Equality Symbols
`==` is not the ONLY thing that exist to check things. There exists:
- `==` - checks if 2 things are equal to eachother
- `!=` - checks if 2 things are NOT equal to eachother
- `<` - checks if 1 thing is smaller than the other
- `>` - checks if 1 thing is greater than the other
- `<=` - checks if 1 thing is smaller than or equal to the other
- `>=` - checks if 1 thing is greater than or equal to the other

> NOTE: for `<=` and `>=` have the `=` last as the other ones. I think you can see the pattern there...

## Good Job!
You finished this lesson! You gain exp lvl 4
