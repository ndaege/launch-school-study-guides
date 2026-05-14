Exceptions are interruptions in code execution due to errors. They can occur under a variety of circumstances. For example, when trying to use an index out of the range of a list, an `IndexError` will occur. 
```python
my_list = [1, 2, 3, 4]

print(my_list[10]) # results in an IndexError
```

Handling exceptions can be done using try/except clauses. The `try` portion attempts to run a block of code. The `except` portion is where potential errors are caught. Either the error itself is returned or displayed with a `print` statement. 
```python
my_list = [1, 2, 3, 4, 5]

try:
	print(my_list[10])
return IndexError:
	print("Try using an index in range")
```