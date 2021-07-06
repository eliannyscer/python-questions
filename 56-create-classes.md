# How are classes created in Python?

Python is an object oriented programming language.Almost everything iis an object, with its properties and methods.

## Create a Class

To create a class, you need to use the keyword `class`:

`Example:`

```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("Ellie", 26)

print(p1.name)
print(p1.age) 

# Output:
Ellie
26
```

## Reference

[Classes and Objects](https://www.w3schools.com/python/python_classes.asp)
