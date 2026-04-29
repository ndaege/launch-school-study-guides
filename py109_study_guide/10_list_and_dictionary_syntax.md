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
