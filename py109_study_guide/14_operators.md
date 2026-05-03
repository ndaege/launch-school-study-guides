### Arithmetic
#### `+`
The `+` operator is used for adding number .
```python
print(3 + 2) # prints 5
```

`-`
The `-` operator is used for subtracting numbers.
```python
print(5 - 4) # prints 1
```

`/`
The `/` operator is used to divide to numbers.
```python
print(6 / 3) # prints 2
```

`//`
The `//` operator is used for floor division, which is division, but the result is rounded down to the nearest integer. 
```python
print(7 // 3) # prints 2
```

`%`
The `%` operator, or modulo, finds the remainder from dividing one number by another. 
```python
print(10 % 3) # prints 1
```

`**`
The `**` operator performs an exponentiation. The left operand is the coefficient, and the right operand is the exponent. 
```python
print(2 ** 3) # prints 8
```


### String
#### `+`
The `+` operator will concatenate two strings together.
```python
print('The ' + 'end.') # prints The end.
```


### List
#### `+`
The `+` operator can add elements to an existing list. 
```python
my_list = [1, 2, 3, 4]
print(my_list + [5, 6, 7, 8])
```


### Comparison
#### `==`
The `==` operator checks for equality in value between the two operands. If the values of the two operands are equivalent, then the comparison equates to `True`. If not, then it equates to `False`.
```python
my_var = 1

if my_var == 1: # evaluates to True
	# run this block
```

#### `!=`
The `!=` operator is the opposite if the `==` operator where '!' means 'not'. So it can be read as 'not equal'. Therefore, this operator is checking that both operators are not equal to one another. If they are not equal, then the comparison evaluates to `True`, `False` otherwise. 
```python
my_var = 1

if my_vara
```

#### `<`
The `<` operator checks to see if the left operand is less than the right operator. 
```python
my_var1 = 1
my_var2 = 2

if my_var 1 < my_var2:
	print("The left operand is smaller.")
```

#### `>`
The `>` operator checks to see if the right operand is greater than the right operator. 
```python
 my_var1 = 1
 my_var2 = 2
 
 if my_var1 > my_var2:
	print("The left operand is larger.")
else: 
	print("The left operand is smaller.") # else block runs
```

#### `<=`
The `<=` operator checks to see if the left operand is less than or equal to the right operand. 
```python
my_var1 = 1
my_var2 = my_var1
my_var3 = 2

if my_var1 <= my_var2:
	print("The left operand is less than or equal to the right operand.")
	
if my_var2 <= my_var3:
	print("The left operand is less than or equal to the right operand.")
```

#### `>=`
The `>=` operator checks to see if the right operand is greater than or equal to the right operand.
```python
my_var1 = 3
my_var2 = my_var1
my_var3 = 1

if my_var1 >= my_var3:
	print("True")
	
if my_var1 >= my_var2:
	print("True")
```


### Logical
#### `and`
The `and` operator compares the truthiness of the left and operands. The comparison will evaluate to `False` in all instances except one, and that is only if both operands are 'truthy.' 
```python
# 1 is truthy
# 0 is falsy
# True is truthy
# [] is falsy

if 1 and 0: # one truthy and one falsy value = False
	print("skip")
else:
	print("False")
	
if [] and 0: # two falsy values = False
	print("skip")
else:
	print("False")
	
if True and 1: # only two truthy values = True
	print("True")
```


#### `or` 
The `or` operator compares the truthiness value of the left and right operands. The comparison will evaluate to `True` in most instances, but one. That occurs when both operands are 'falsy'. Put simply, at least one operand must be 'truthy' for the comparison to evaluate to `True`.
```python
if [] or 1: # right operand is truthy, so the comparison evaluates to True
	print("True")

if True or 7: # both operands are truthy, so the comparison evaluates to True
	print("True")
	
if [] or 0: # both operands are falsy, so the comparison evaluates to False
	print("False")
```


#### `not`
The `not` operator flips the truthiness value of whatever comes right after.
```python
print(not True) # False

print(not False) # True
```


### Identity
#### `is`
The `is` operator checks to see if two objects are the same. Even if the values of one object are the same as another, that does not necessarily mean that they are the same object. Returns `True` only if the objects are the same. 
```python
my_list1 = [1, 2, 3]
my_list2 = my_list1

my_nested1 = [[1, 2], [3, 4]]
my_nested2 = [[1, 2], [3, 4]]

print(my_list1 is my_list2) # prints True
print(my_nested1 is my_nested2) # prints False
```


#### `is not`
The `is not` operator checks to see of two objects are are different. If they are, then `True` is returned. `False`, otherwise. 
```python
my_list1 = [1, 2, 3]
my_list2 = my_list1

my_nested1 = [[1, 2], [3, 4]]
my_nested2 = [[1, 2], [3, 4]]

print(my_list1 is not my_list2) # prints False
print(my_nested1 is not my_nested2) # prints True
```


#### Operator precedence
Operator precedence determines the evaluation order of expressions. Some operators have higher precedence and are preferred for evaluation before others, or they are said to bind more tightly to its operands. Precedence and evaluation order starts from left to right. However, with so many operators and precedence rules, it is preferred to use parentheses to show intent. This helps make longer and more complex expressions more readable. 