Booleans represent the values `True` or `False`. Booleans one part to determining how code should move forward. For example, with `while` loops, the loop will run until it's condition evaluates to False. However, how does Python determine the condition evaluation. It uses truthiness, which is the concept that certain values evaluate to `True` and others to `False`.
Some examples of 'truthy' values are: 
- numbers that are less than or greater than zero
- non-empty collections, even if the elements are None or whitespace characters
- True
- strings with at least one character, even whitespace

Some examples of 'falsy' values are: 
- the number zero
- any empty collection
- False
- empty strings
- None

Here are some code examples:
```python
my_str = ' ' # truthy
num = 3 # truthy
my_list = [1, 2, 3] # truthy

empty_str = '' # falsy
empty_list = [] # falsy
zero = 0 # falsy

falsy_list = [empty_str, empty_list, zero] # truthy
truthy_list = [my_str, num, my_list] # truthy

if falsy_list: # evaluates to True
  print("The list is truthy") # this prints because the list isn't empty, despite the list elements all containing falsy values. 
else:
  print("The list is falsy")
  
if truthy_list: # evaluates to True
  print("The list is truthy") # same as line 13, this list is non-empty, so this line prints
else:
  print("The list is falsty")
```