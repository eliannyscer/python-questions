# What does tkinter mean?

- It is one of the most commonly used modules for creating GUI applications in Python as it is simple and easy to work with.

- You don’t need to worry about the installation of the Tkinter module separately as it comes with Python already.

- Tkinter provides a fast and easy way to create GUI applications and a powerful object-oriented interface.

## Creating a GUI application using Tkinter

It is an easy task. All you need to do is perform the following steps:

- Import the Tkinter module.

- Create the GUI application main window.

- Add one or more of the widgets to the GUI application.

- Enter the main loop.

`Example:`

```python
from tkinter import *
# main window
root = Tk()
root.title("New window with tkinter")
root.configure(background="black")

root.mainloop()
```

You will display a window like the follow:

![New window]()

## Additional information

`Graphical User Interface(GUI)` - It is a form of user interface which allows users to interact with computers through visual indicators using items such as icons, menus, windows, etc.

## References

[Introduction to Tkinter](https://www.geeksforgeeks.org/introduction-to-tkinter/)

[Python - GUI Programming (Tkinter)](https://www.tutorialspoint.com/python/python_gui_programming.htm)
