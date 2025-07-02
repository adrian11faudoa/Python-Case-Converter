Subject:

    List Comprehension:
is a construct that allows you to generate a new list by applying an expression to each item in an existing iterable and optionally filtering items with a condition

A basic list comprehension consists of an expression followed by a for clause:

Example Code:
```
    spam = [i * 2 for i in iterable]
```

List comprehensions accept conditional statements, to evaluate the provided expression only if certain conditions are met:
Example Code:
```
    spam = [i * 2 for i in iterable if i > 0]
```

Else clause
Example Code:
```
    spam = [i * 2 if i > 0 else -1 for i in iterable]
```

Note that, differently from the if clause, the if/else construct must be placed between the expression and the for keyword.


the .strip() string method, which removes from a string any leading or trailing characters among a set of characters passed as its argument.

Example Code:
```
    original_string = "_example_string_"
    clean_string = original_string.strip('_')
```
Result: 'example_string'
