# Resume

Questions 21-30

## Q21. What does [::-1] do?

It means that for a given string/list/tuple, you can slice the said object using the format:

`<object_name>[<start_index>, <stop_index>, <step>]`

## Q22. Randomize the items of a list in place

The random module provides a shuffle() function that returns a sequence with its elements randomly.

## Q23. Iterators

An `iterable` is any object that can return an iterator and an `iterator` is the object used to iterate over an iterable object. This implements __iter__ and __next__ methods.

## Q24. Generate random numbers

Random module is the standard module that is used to generate a random numbers. The function random.random() is a absolute basic random number generation.

## Q25. Difference between range and xrange

The principal difference is that range returns a Python list object and xrange returns an xrange object.

This means that xrange doesn’t actually generate a static list at run-time like range does. It creates the values as you need them with a special technique called yielding.

## Q26. Comments

A single line comment can be added by using the `hash (#)`character. The `hash (#)` is added for every line that should be commented.

## Q27. Pickling and un-pickling

* `Pickling` - It is a process of converting a `object` into a `bytes stream` and  it can be stored into a file.

`Unpickling` - It is inverse operation of pickling. Unpickling is a process where a `byte stream` is converted back into a `object`.  

## Q28. Generators

It is Functions that return iterable items to do it use the `yield keyword` instead than `return`. If the body of a `def` function contains `yield`, the function automatically becomes a generator function.

## Q29. How to capitalize the first letter in a string

Using the function capitalize() because this convert the first letter of a string in a capital letter. Syntax -  `string.capitalize()`.

## 30. How will you convert a string to all lowercase?

To convert String to lowercase, you can use `lower()` function on the String. `String.lower()` function returns a string with all the characters of this string converted to lower case.
