#### `print`
The `print` function displays text on the terminal. It's useful for providing messages to a command-line user, or for debugging. The `print` function returns None, by default. The `sep` keyword argument can be passed to provide a delimiter to multiple objects. 
```python
print("This print call returns None") # returns None

print(1, 2, 3, 4, 5, sep='-') # prints 1-2-3-4-5
```


#### `input`
The `input` function stores user input to be used later. 
```python
user_input = input("What is your name? ")

print(user_input) # prints the input from the user
```