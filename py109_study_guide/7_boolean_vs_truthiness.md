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
my_str = ' '
num = 3
my_list = [None]
```