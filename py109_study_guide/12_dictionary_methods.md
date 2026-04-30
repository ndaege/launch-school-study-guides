#### dict.keys()
The `keys()` method is a dictionary method that returns a dictionary view object containing all of the dictionary's keys.
```python
my_dict = {'a': 1, 'b': 2, 'c': 3}

print(my_dict.keys()) # prints dict_keys(['a', 'b', 'c'])
```


#### dict.values()
The `values()` method is a dictionary method that returns a dictionary view object containing all of the dictionary's values. 
```python
my_dict = {'a': 1, 'b': 2, 'c': 3}

print(my_dict.values()) # prints dict_values([1, 2, 3])
```


#### dict.items()
The `items()` method is a dictionary method that returns a dictionary view object containing all of the dictionary's key-value pairs. 
```python
my_dict = {'a': 1, 'b': 2, 'c': 3}

print(my_dict.items()) # prints dict_items([('a': 1), ('b': 2), ('c': 3)])
```


#### dict.get()
The `get()` dictionary method returns the value of the passed key. If the key is not in the dictionary, then `None` is returned by default. Otherwise, the user can pass another value to be returned. 
```python
my_dict = {'a': 1, 'b': 2, 'c': 3}

print(my_dict.get('d')) # returns None
print(my_dict.get('d', "Specified key not found")) # prints Specified key not found
```