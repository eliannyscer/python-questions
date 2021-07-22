# How do you make 3D plots/visualizations using NumPy/SciPy?

Like 2D plotting, 3D graphics is beyond the scope of NumPy and SciPy, but just as in the 2D case, packages exist that integrate with NumPy. `Matplotlib` provides basic 3D plotting in the mplot3d subpackage, whereas Mayavi provides a wide range of high-quality 3D visualization features, utilizing the powerful VTK engine.

`Example`:

```python
import matplotlib.pyplot as plt, numpy as np
from mpl_toolkits.mplot3d import Axes3D

v= np.array([[1,2,3], [4,5,6], [7,8,9]])
fig = plt.figure()
ax = fig.add_subplot(111, projection='3d')
ax.plot(v[:,0],v[:,1],v[:,2])
plt.show()
```

![plot](https://i.stack.imgur.com/wkK4E.png)

## Additional information

`Matplotlib` - It is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK.

## References

[Plot](https://stackoverflow.com/questions/40351026/plotting-a-simple-3d-numpy-array-using-matplotlib)

[Matplotlib](https://forums.wikitechy.com/question/how-do-you-make-3d-plots-visualizations-using-numpy-scipy/)

[Matplotlib definition](https://en.wikipedia.org/wiki/Matplotlib)
