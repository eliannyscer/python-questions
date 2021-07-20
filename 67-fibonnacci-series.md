# Write a program to produce Fibonacci series in Python

`What is Fibonacci Series?` - It is a series of numbers formed by the sum of the two preceding numbers in the series.

```python
 0,1,1,2,3,5
```

* The `1` is found by sum the two numbers before it (0+1)

* The `2` is found by sum the two numbers before it (1+1)

* The `3` is found by sum the two numbers before it (2+1)

* The `5` is found by sum the two numbers before it (2+3)

`It is done until the number of terms you want or requested by the user`.

`Example:`

```python
e = int(input("Enter length: "))
# First element of series
l = 0
# Second element of series
i=1
if e<=0:
    print("The requested series is",l)
else:
    print(l,i,end=" ")
    for x in range(2,e):
        next=l+i
        print(next,end=" ")
        l = i
        i = next
```

`Output:`

```text
# Using the number 8 as input
0 1 1 2 3 5 8 13

# Using a negative number:
The requested series is 0
```

## References

[What is Fibonacci Series?](https://www.edureka.co/blog/python-fibonacci-series/)

[Fibonacci series explanation](https://www.pythonpool.com/fibonacci-series-in-python/)
