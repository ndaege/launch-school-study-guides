## Implicit Type Coercion
Implicit type coercion occurs Python performs the conversion from one data type to another. This most commonly occurs when arithmetic operations are performed on a mix of number-based data types. For example: 
- integers and floats

To demonstrate this code, we can look at the following code:
```python
starting_amount = 5
change = 1.50

money_before_transaction = starting_amount - change
print(money_before_transaction) # 3.50
```

In order for the previous code to be performed, `money_before_transaction` must be evaluated. In order to do this, Python converts `starting_amount` to a float type, so that the subtraction operation can be performed. 


## Explicit Type Coercion
Explicit type coercion happens when the programmer specifically uses constructor methods to convert an object's data type to another. For example, when using:
- int()
- str()
- float()

To demonstrate this, review the following code: 
```python
user_input = int(input("Please provide a number between 1 - 10: "))
```

In the code above, `user_input` takes in user input. The `input()` method always takes in strings. When the user passes in input, it's a string, even when passing in what they think is a number. In order to manipulate the passed in data as intended, the string must be implicitly converted to an integer data type with the `int()` method. 