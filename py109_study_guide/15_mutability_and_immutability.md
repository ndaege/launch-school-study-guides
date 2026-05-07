#### Immutability
Immutability is when the value of a variable cannot be changed. This occurs with data types like integers, strings, floats, booleans, frozensets, etc. Examples: 
```python
my_str = "text"
my_int = 5

my_str + " sequence"
print(my_str)

my_int += 5
print(my_int)
```

And the same happens when the variables are passed to a function:
```python
my_str = "text"

def string_concatenator(string):
    return string + " sequence"
    
string_concatenator(my_str)
print(my_str) prints # text
```


#### Mutability
Mutability is the concept that the value of a variable can be changed after assignment. Mutable data types include, but aren't limited to: lists, dictionaries, sets, etc. Examples of mutability: 
```python
my_list = [1, 2, 3, 4]

my_list.append(5)

print(my_list) # prints [1, 2, 3, 4, 5]

my_dict = {'a': 1, 'b': 2}

my_dict.update({'c': 3})

print(my_dict) # {'a': 1, 'b': 2, 'c': 3}
```

Mutability also applies to functions: 
```python
my_list = [1, 2, 3, 4]

def list_update(num):
	my_list.append(num)
	
list_update(5)
print(my_list) # prints [1, 2, 3, 4, 5]
```