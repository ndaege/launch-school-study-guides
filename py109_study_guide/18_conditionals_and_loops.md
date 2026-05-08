### for
The `for` loop is a loop that iterates through fixed sequences. Its syntax allows programmers to omit counting indexes. Instead, the `for` loop keeps track of the indexes. Example: 
```python
numbers = list(range(1, 11))

for number in numbers:
	print(number)
```

In the code above, the loop iterates through the finite list and prints each number individually. This type of loop is great when searching for elements in a list, or picking out elements with certain values. 
```python
numbers = list(range(1, 11))

for number in numbers:
	if number % 2 == 0:
		print(number) # print only even numbers
```


### while
The `while` loop is best when iterating through sequences where the programmer is unsure when the end of the loop will be. For example, when the loop must continue until a certain key is pressed. They keep iterating until the condition is `False`. For example: 
```python
while True:
	user_input = input("Would you like to continue? y/n\n")
	if user_input == 'y':
		continue
	else:
		break
 ```