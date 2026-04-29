Ranges are sequences of numbers in Python. They are created using the `range()` constructor function. Ranges are a special type of object that can't be printed. Instead, they must be passed into a `list()` constructor, or other iterable data type, in order for the sequence of numbers to be used or see in a print statement. Ranges can be created using a 'start', 'stop', and 'step'. The 'start' is the range's starting number, the 'stop' is the last number in the sequence, exclusive, and the 'step' is the number increment that the range will use to determine the sequence of numbers between the 'start' and 'step'. The default range function is passed the 'stop', starts at 0, and has a 'step' of 1. Below are some examples: 

```python
my_range1 = list(range(6)) # [0, 1, 2, 3, 4, 5] the 'stop' is not included
my_range2 = list(range(5, 11)) # [5, 6, 7, 8, 9, 10]
my_range3 = list(range(10, 21, 2)) # [10, 12, 14, 16, 18, 20] # increment by 2
```