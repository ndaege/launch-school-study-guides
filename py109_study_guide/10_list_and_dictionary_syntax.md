### List Syntax
#### Indexing
Lists use zero-based indexing to access elements. 
```python
my_list = [1, 2, 3, 4]

print(my_list[2]) # prints 3
```

#### IndexError
When accessing list elements, one must use an index that lies with the list's minimum and maximum index amount, otherwise, the program will fail due to `IndexError`. 

```python
my_list = [1, 2, 3, 4]

print(my_list[5]) # IndexError: index out of range
```


#### Reverse indexing
Accessing the last or elements in reverse, can be done using negative numbers. For example, to access the last element: 
```python
my_list = [1, 2, 3, 4]

print(my_list[-1]) # prints 4
```

Similarly with regular indexing, one must ensure that the reverse index is within the range of index elements. 


#### List traversal
Lists can be traversed using for and while loops. Since lists are finite, they are generally traversed using for loops, and the syntax is easier to follow, since one doesn't have to keep track of the indexes. Below is an example of traversing a list with a for loop: 
```python
my_list = list(range(1,11))

for i in my_list:
  print('The number', str(i)) 
  
# Example output
# The number 1
# The number 2
# The number 3
# ...etc.
```


#### Slicing
Lists can also be accessed with slicing, to extract the desired elements. For example: 
```python
my_list = list(range(1, 11))

evens = my_list[1::2]
print(evens) # prints [2, 4, 6, 8, 10]
```
### ----------------------------------------------------

### Dictionary Syntax
#### Key-based Access
Dictionaries are collections of key-value pairs. In order to access the values of a dictionary, the dictionary key, that corresponds to the value is used. 
```python
my_dict = {'a': 3, 'b': 2, 'c': 1}

print(my_dict['a']) # key-based access, prints 3
```


#### KeyError
When accessing dictionaries, one must be careful when using key-based access. If the key is not in the dictionary, it will result in a `KeyError`. 
```python
my_dict = {'a': 3, 'b': 2, 'c': 1}

print(my_dict['d']) # result in KeyError, 'd' key not in my_dict
```

#### Avoiding KeyError
To avoid the `KeyError`, one can either use the `in` membership operator or the `get()` method. Below are examples of how they work: 
```python
my_dict = {'a': 3, 'b': 2, 'c': 1}

# membership
if 'd' in my_dict:
	print("yes")
else:
    print("no")
    
# get method
print(my_dict.get('d', 'Key not found'))
```
