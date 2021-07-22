# How do you calculate percentiles with Python/ NumPy?

The nth percentile of a dataset is the value that cuts off the first n percent of the data values when all of the values are sorted from least to greatest.

We can calculate percentiles with the following code:

```python
import numpy as np
array = np.array([1, 2, 3, 4, 5])
# return 50th percentile, e.g median
percentile = np.percentile(array, 50) 
print(percentile)

# Output:
3
```

## Additional information

`How to Calculate Percentiles in Python?`

`numpy.percentile()function` is used to compute the nth percentile of the given data (array elements) along the specified axis.

`Syntax`: numpy.percentile(arr, n, axis=None, out=None).

### Parameters

`arr`:input array.

`n`: percentile value.

`axis`: axis along which we want to calculate the percentile value. Otherwise, it will consider arr to be flattened(works on all the axis). axis = 0 means along the column and axis = 1 means working along the row.

`out`:Different array in which we want to place the result. The array must have same dimensions as expected output.

`Return`:nth Percentile of the array (a scalar value if axis is none)or array with percentile values along specified axis.

## Reference

[Code to calculate percentiles](https://stackoverflow.com/questions/2374640/how-do-i-calculate-percentiles-with-python-numpy)

[Numpy Percentile](https://numpy.org/devdocs/reference/generated/numpy.percentile.html#numpy.percentile)

[numpy.percentile() in python](https://www.geeksforgeeks.org/numpy-percentile-in-python/)

[How to Calculate Percentiles in Python](https://www.statology.org/percentiles-in-python/)
