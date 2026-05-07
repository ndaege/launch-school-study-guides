Pass by object reference dictates the behavior of objects when passed to functions in Python. It is sort of a combination of pass by value and pass by reference. Where, values that are immutable behave as though they are pass by value, and values that are mutable, behave as though they are pass by reference. 

#### Pass by object reference with immutable values
```python
my_str = 'abc'

def string_concat(text): # like passing the value of the object
	return text + 'def'
	
string_concat(my_str)
print(my_str) # prints 'abc'
```


#### Pass by object reference with mutable values
```python
my_list = [1, 2, 3, 4]

def add_to_list(lst): # like passing a reference to the object
	return lst.append(5)
	
add_to_list(my_list)
print(my_list) # prints [1, 2, 3, 4, 5]
```
