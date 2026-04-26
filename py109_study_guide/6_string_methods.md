Strings are a common and versatile data type. As a result, there are many string methods. Some of the most common are below. 
#### capitalize

The `capitalize` method takes in a string and makes the first letter uppercase.
```python
my_str = 'apple'

print(my_str.capitalize()) # prints Apple
```


#### swapcase

The `swapcase` method changes lowercase letters to uppercase letters, and vice-versa. 
```python
my_str = 'aPPLE'

print(str_str.swapcase()) # prints Apple
```


#### upper

The `upper` method makes all characters in a string uppercase. 
```python
my_str = 'apple'

print(my_str.upper()) # prints APPLE
```


#### lower
The `lower` method makes all characters in a string lowercase.
```python
my_str = 'ApPlE'

print(my_str.lower()) # prints apple
```


#### isalpha
The `isalpha` method checks if a string is all letter characters. If is is, it returns True. Otherwise, it returns False. 
```python
my_str = 'apple'
other_str = 'february 12'

print(my_str.isalpha()) # prints True
print(other_str.isalpha()) # prints False
```


#### isdigit
The `isdigit` method checks if a string is all digit characters. If it is, it returns True. Otherwise, it returns False. 
```python
my_str = 'apple'
num_str = '100'

print(my_str.isdigit()) # prints False
print(num_str.isdigit()) # prints True
```


#### isalnum
The `isalnum` method checks of a string is a mix of letter and digit characters. If it is, it returns True. Otherwise, it returns False. 
```python
alnum_string = 'abc123'
non_alnum = ' '

print(alnum_string.isalnum()) # prints True
print(non_alnum.isalnum()) # prints False
```


#### islower
The `islower` method checks if all letter characters in a string are lowercase. If they are, it returns True. False, otherwise. 
```python
lower_string = 'lower'
upper_string = 'UPPER'

print(lower_string.islower()) # prints True
print(upper_string.islower()) # prints False
```


#### isupper
The `isupper` method checks if all letter characters in a string are uppercase. If they are, it returns True. False, otherwise. 
```python
lower_string = 'lower'
upper_string = 'UPPER'

print(lower_string.isupper()) # prints False
print(upper_string.isupper()) # prints True
```


#### isspace
The `isspace` method checks to see if all characters in a string are whitespace, tabs, or newline characters. If they are, it returns True. False, otherwise. 
```python
space_string = ' '
no_space = 'bunchawords'
nothing = ''

print(space_string.isspace()) # prints True
print(no_space.isspace()) # prints False
print(nothing.isspace()) # prints False
```


#### strip
The `strip` method removes any whitespace from both the right and left-hand sides of a string. 
```python
str_with_whitespace = ' television '
print(str_with_whitespace.strip()) # prints television
```


#### rstrip
The `rstrip` method removes any whitespace from the right-hand side of a string. 
```python
end = 'The end. '
print(end.rstrip()) # prints The end.
```


#### lstrip
The `lstrip` method removes any whitespace from the left-hand side of a string. 
```python
beginning = ' The beginning...'
print(beginning.lstrip()) # prints The beginning...
```


#### replace
The `replace` method takes two string parameters. The first parameter is the old string to look for. The second parameter is the new string used to replace the old string. 
```python
my_str = "This year's report showed placeholder growth."
print(my_str.replace('placeholder', 'sky-high')) # prints This year's report showed sky-high growth. 
```


#### split
The `split` method modifies a character used to split sequences of characters into elements of a list. By default, the `split` method separates sequences of characters by whitespace. Otherwise, one could pass a delimiter into the method, and that will be used to split the sequences. 
```python
my_str = 'Let sleeping dogs lie'
print(my_str.split()) # prints ['let', 'sleeping', 'dogs', 'lie']

csv_str = 'first_name,last_name,dob'
print(csv_str.split(',')) # prints ['first_name', 'last_name', 'dob']
```


#### find
The `find` method takes a sub-string as an argument, then it searches for the first appearance of that sub-string and returns the first index where it is found. 
```python
my_str = "The apple doesn't fall far from the tree."

print(my_str.find("app")) # 5
```



#### rfind
The `rfind` method takes a sub-string as an argument, then it searches from the end to the beginning to find the first index where the sub-string is found. 
```python
my_str = "The apple doesn't fall far from the tree."

print(my_str.rfind("fa")) # prints 23
```