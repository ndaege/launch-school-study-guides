#### list.append()
The `append()` method adds an elements to the end of the list. This methods mutates the calling list object. 
```python
my_list = [1, 2, 3, 4]

my_list.append(5)

print(my_list) # prints [1, 2, 3, 4, 5]
```


#### list.pop()
The `pop()` method, by default removes an element from the end of a list. Otherwise, it removes the element at the specified index. The method returns the element that was removed. This method mutates the caller. 
```python
my_list = [1, 2, 3, 4, 5]

print(my_list.pop()) # prints 5
print(my_list) # prints [1, 2, 3, 4]

print(my_list.pop(2)) # prints 3
print(my_list) # prints [1, 2, 4]
```


#### list.reverse()
The `reverse()` method reverses the order of a list in-place, thereby mutating the calling list object. 
```python
my_list = [1, 2, 3, 4, 5]

my_list.reverse()

print(my_list) # prints [5, 4, 3, 2, 1]
```

