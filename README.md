# Introduction to Python
This readme will break down the exercises completed during the data scientist track with python.

## Python Basics
### The Python Interface
* Simple calculations

``` Python
# Print the sum of 7 and 10
print(7+10)
```
### When to use Python?
* Python is a pretty versatile language. For which applications can you use Python?
```
[ ] You want to do some quick calculations.
[ ] For your new business, you want to develop a database-driven website.
[ ] Your boss asks you to clean and analyze the results of the latest satisfaction survey.
[x] All of the above.
```
### Any comments?
* Above the ``print(7+10)``, add the comment ``#Addition``
```Python
# Addition
print(7+10)
```
### Python as a calculator
* Suppose you have $100, which you can invest with a 10% return each year. After one year, it's 100×1.1=110 dollars, and after two years it's 100×1.1×1.1=121. Add code to calculate how much money you end up with after 7 years, and print the result.
```python
# How much is your $100 worth after 7 years?
print(100 * 1.1 ** 7)
```
### Variable Assignment
* Create the variable ``savings`` with the value 100.
* Type ``print(savings)`` to view the variable
```python
# Create a variable savings
savings = 100
# Print out savings
print(savings)
```
### Calculations with variables
* Create a variable ``growth_multiplier``, equal to ``1.1``.
* Create a variable, ``result``, equal to the amount of money you saved after ``7`` years.
* Print out the value of ``result``.
```python
# Create a variable savings
savings = 100
# Create a variable growth_multiplier
growth_multiplier = 1.1
# Calculate result
result = savings * growth_multiplier ** 7
# Print out result
print(result)
```
### Other variable types
* Create a new string, ``desc``, with the value ``compound interest``.
* Create a new boolean, ``profitable``, with the value ``True``.
```python
# Create a variable desc
desc = "compound interest"
profitable = True
```

### Guess the type
* Use the ``type()`` function to determine the type of ``a`` ``b`` and ``c``.
```python
In [1]: type(a)
Out[1]: float

In [1]: type(b)
Out[1]: str
	
In [1]: type(c)
Out[1]: bool
```

```
[ ] a  is of type  int,  b  is of type  str,  c  is of type  bool
[ ] a  is of type  float,  b  is of type  bool,  c  is of type  str
[x] a  is of type  float,  b  is of type  str,  c  is of type  bool
[ ] a  is of type  int,  b  is of type  bool,  c  is of type  str
```
### Operations with other types
* Calculate the produce of ``savings`` and ``growth_multiplier``. Store the result in ``year1``.
* What do you think the resulting type will be? Find out by printing out the type of ``year1``.
* Calculate the sum of ``desc`` and ``desc`` and store the result in a new variable ``doubledesc``.
* Print out ``doubledesc``. Did you expect this?
```python
savings = 100
growth_multiplier = 1.1
desc = "compound interest"

# Assign product of savings and growth_multiplier to year1
year1 = savings * growth_multiplier

# Print the type of year1
print(type(year1))

#Assign sum of desc and desc to doubledesc
doubledesc = desc + desc

#Print out doubledesc
print(doubledesc)
```

### Type conversion
* Hit _Run Code_ to run the code. Try to understand the error message.
* Fix the code such that printout runs without errors; use the function ``str()`` to convert teh variables to strings.
* Convert the variable ``pi_string`` to a float and store this float as a new variable, ``pi_float``.
```python
# Definition of savings and result
savings = 100
result = 100 * 1.1 ** 7

# Fix the printout
print("I started with $" + str(savings) + " and now have $" + str(result) + ", Awesome!")

# Definition of pi_string
pi_string = "3.1415926"

# Convert pi_string into float: pi_float
pi_float = float(pi_string)
```
### Can Python handle everything?
Which of these will throw an error?
```
[ ] "I can add integers, like " + str(5) + " to strings."
[ ] "I said " + ("Hey " * 2) + "Hey!"
[x] "The correct answer to this multiple choice exercise is answer number " + 2
[ ] True + False
```

## Python Lists
