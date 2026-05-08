### Naming conventions
For naming conventions see [[1_naming_conventions]]. 

### Initialization, assignment, reassignment
Initialization is the creation of a new variable, assignment is providing the newly created variable with a value. In Python, initialization and assignment generally happen at the same time. It looks like this `a = 'a'` . This is the initialization of the `a` variable and 'assigning' is the value of 'a'.  Reassignment occurs when an already initialized variable is assigned a different value than was previously assigned. So, if we take the previous `a` variable and assign it a new value. Like so: `a = 'b'`. 

### Scope
The scope of a variable determines where the variable can be used. There is global scope, which allows a variable to be accessed anywhere in code. Function scope is an inner layer from global scope. It is called a local scope. Function scope can access variables in the global scope, but not vice versa. Only that function's scope or its nested functions can access it's variables.
```python
my_str = 'example' # global scope variable

def my_func():
	this_var = 'example2' # function scope variable
```

### Global
The `global` keyword allows direct access to a global variable and prevents variable shadowing. 
```python
my_var = 'value'

def my_func():
	global my_var
	my_var += ', more values'
	
	return my_var
	
print(my_func()) # prints: value, more values
print(my_var)    # prints: value, more values
```

In the code above, if the `global` keyword isn't used to specify that the `my_var` variable being used is from the local scope, then the code would fail. 
```python
my_var = 'value'

def my_func():
	my_var += ', more values' # this line is trying to reference a function scope variable my_var before it has been assigned, resulting in a NameError
	
	return my_var 
	
print(my_func())
print(my_var)   
```


### Variables as pointers
Variables as pointers, means that a variable can hold the reference to a value as its value. For example: 
```python
my_var1 = 'a'
my_var2 = my_var1 # this is a pointer to my_var1
```


### Variable shadowing
Variable shadowing is the concept that a local scope variable with the same name, but assigned a different value as a global scope variable, is a different variable than the one in the global scope. It is a separate local variable. Furthermore, within the local scope, the local scope variable's value will be used for operations, instead of the global scope variable. 
```python
my_var = 3

my_func():
	my_var = 4
	print(my_var)
	
my_func() # prints 4, because the my_var variable in the function scope is assigned a value of 4
print(my_var) # this now refers to the global scope variable, which is assigned a value of 3
```