Book of contents:


# Lesson 2 - Variables

In this lesson, we will learn about variables.

# What *are* variables??
Variables are containers that store values like strings and integers.  
Variables are like **Boxes**. You put a **paper** into the box, and use the `print` function to take out that paper and read it.

# Variables in action
To make a variable, we decide how to call it and then put an `=` then the value:
```python
var = "Value"
```
> TIP: to make the code more readable, us, programmers, put spaces next to the `=`.

Now let's print that `var`!
```python
var = "Value"

print(var)
```
As you can see, we didn't put any `""`. This is because if there were `""`, then the console will print just `var`.

# How to join strings to variables:

To put a string next to a variable in the `print` function, we use `+` or `,` to make this.  
### Example 1:

```python
var = "Value"

print("The value is " + var)
```
`Output: The value is Value`

Here, we used `+`. We needed to put a space in the string because `+` directly joins the two together.

### Example 2:
```python
var = "Value"
print("The value is", var)
```
`Output: The value is Value`

In this example we used `,`.  As you can see, this time we didn't put any spaces. This is because the `,` joins the two but with a space.

# Naming The Variable
The variable doesn't allow spaces in its name, so we use *Cases*. Cases, here, mean how we name the variable. There are only two cases:
- The Snake Case - We name a variable with multiple words like this: `snake_case`
- The Camel Case - We name a variable with multiple words like this: `camelCase`  
So basically, The snake case uses `_` for spaces and Camel Case uses Capital Letters For new Words
> NEED TO KNOW THIS: variables are usually written with small letter like this: `variable` and not: `Variable`. If you are prefering Camel Case, You need to write variables like in the example above.

## Good Job!
You finished this lesson! You now have experience!
