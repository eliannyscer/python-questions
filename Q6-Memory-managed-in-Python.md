# How is memory managed in Python?

* Python has an garbage collector to recycles all the unused memory to make it available for other objects

## Important to know

### Why should you care?

Knowing about memory management helps you write more efficient code

### How are python objects stored in memory?

Name --> References --> Objects

A name is just a label for an object and each object can have lots of names those names reference that objects. A  reference is a name or a container objet pointing at another object

### Different types of objects

* Simple ( number and strings)
* Containers ( dict, list ,classes)