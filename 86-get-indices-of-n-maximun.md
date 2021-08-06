# How to get indices of N maximum values in a NumPy array?

NumPy proposes a way to get the index of the maximum value of an array via `np.argmax`.

We can get the indices of N maximum values in a NumPy array using the below code:

```python
import numpy as np
arr = np.array([1, 3, 2, 4, 5])
arr.argsort()[-3:][::-1]
array([4, 3, 1])
```

## References

[Code to get N maximum values](https://stackoverflow.com/questions/6910641/how-do-i-get-indices-of-n-maximum-values-in-a-numpy-array)

[Other examples](https://www.semicolonworld.com/question/43452/how-do-i-get-indices-of-n-maximum-values-in-a-numpy-array)
