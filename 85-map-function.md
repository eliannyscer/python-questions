# What is map function in Python?

It takes two inputs as a function and an iterable object. The function that is given to `map()` is a normal function, and it will iterate over all the values present in the iterable object given.

`Syntax:`

```python
map(function, iterables)
```

`Function` - It is Required the function to execute for each item.

`Iterable` - It is Required a sequence, collection or an iterator object. You can send as many iterables as you like, just make sure the function has one parameter for each iterable.

`Example` - Make new colors:

```python
def new_colors(a, b):
  return a + b

result = map(new_colors, ("Purple", "Orange"), ("Yellow", "Pink"))

print(list(result))

# Output:
['PurpleYellow', 'OrangePink']
```

`Example` - Calculate the length of each word in a tuple:

```python
def colors(c):
  return len(c)

result = map(colors, ("Purple", "Pink", "Orange"))

print(list(result))

# Output:
[6, 4, 6]
```

## References

[How map() function work](https://www.guru99.com/python-map-function.html#3)

[Python map() Function](https://www.w3schools.com/python/ref_func_map.asp)
