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
### `and`
The `and` operator compares the truthiness of the left operand, and the truthiness of the right operand. The comparison will evaluate to `False` in all instances except one, and that is only if both operands are 'truthy.' 
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




