# What is a dictionary in Python?

* Dictionaries are used to store data values in key:value pairs.

* It is a collection which is ordered, changeable and does not allow duplicates.

`Example-1` - Printing 1 value:

```python
phone_book = {"Name": "Ellie","Surname": "Brown","Number_phone": "654 789 9543"}
print(phone_book["Number_phone"])

# Output:
654 789 9543
```

`Example-2` - Other way tho organize the dictionary:

```python
phone_book = {"Name": "Ellie",
              "Surname": "Brown",
              "Number_phone": "654 789 9543"}
print(phone_book)

# Output:
{'Name': 'Ellie', 'Surname': 'Brown', 'Number_phone': '654 789 9543'}
```

## Additional information

* `Changeable` - We can change, add or remove items after the dictionary has been created.

* `Ordered` - It means that the items have a defined order, and that order will not change.

* `Duplicates not allowed` - Dictionaries cannot have two items with the same key, is there is two keys with the same name it will use the last added.

`Example:`

```python
# There is to keys called "Name"
phone_book = {"Name": "Ellie",
              "Name": "Mary",
              "Surname": "Brown",
              "Number_phone": "654 789 9543"}
print(phone_book["Name"])

# Output:
Mary
```

## Reference

[Dictionary definition and examples](https://www.w3schools.com/python/python_dictionaries.asp)
