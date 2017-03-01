# lets-write-python
We're set up, we've been through some syntax basics with the first Edx course. Now can we write some damn python code?! 

A great place to [start reading](http://docs.python-guide.org/en/latest/writing/style/)

###Conditionals - aka if statements
```python
if day == "Saturday":
  print("Yay!")
else:
  print("Meh.")
```
[Read through this](http://www.openbookproject.net/books/bpp4awd/ch04.html)

###Flow control - aka loops
`for` loops vs `while` loops
```python
def my_for_loop():
  for number in range(1,6):
    print(number)

def my_while_loop(number):
  number = number - 1
  while n > 0:
    print(number)
```
A `for` loop must iterate over a collection of things. In this way it is finite. However a while loop will continue as long as it's conditional statement evaluates to `True`. Why could this be dangerous? The dreaded infinite loop:
```python
n = 10
while n > 0:
  print(n)
```
This will end up printing `10` until the end of time. 

###List comprehensions
Making lists! A simple example:
```python
numbers = [1, 2, 3, 4, 5]
empty_list = []
for number in numbers:
  if number % 2 == 0:
    empty_list.append(number)
  else:
    pass
 ```
 ###Functions
 
 Functions have the standard format:
 ```python
 def function_name(parameter_1, parameter_2):
    calculations/logic happen here
    return result
 ```
 Parameters can be given default values. If the value is not specified, the default value will be used in the function. 
 ```python
 def function(parameter_1, parameter_2 = 5)
 ```
[More on functions and parameters](https://www.tutorialspoint.com/python/python_functions.htm)



