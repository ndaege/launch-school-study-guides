Slicing is a notation used for sequence objects like tuples, lists, and strings. It allows the extraction of substrings or only the desired elements of a list. For example: 
```python
my_list = [1, 2 ,3, 4, 5, 6, 7, 8]
numbers_up_to_5 = my_list[:5] # prints [1, 2, 3, 4, 5]

my_text = 'You are who you choose to be.'

print(my_text[16:22]) # prints choose

my_tuple = (1, 2, 3)

print(my_tuple[1:]) # prints (2, 3)
```