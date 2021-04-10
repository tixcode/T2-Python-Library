# T2 Python Library
T2 Python Library - 2 Tkinter

##### How to install: https://github.com/tixcode/T2-Python-Library/releases/tag/1.0.0

# Documentation
First, go to the file `main.py` already created by the developer - it already has two lines of code:
```py
import t2
from t2 import window
```
With `import t2` we import the library itself, this is mandatory, and a second line - `from t2 import window` - with this we import the main class - window. Without these two lines the library will not work.

## Methods and Variables

`window.root` - Invoke application window

`window.size(x, y)` - Set size for window, x and y are optional arguments. 

`window.text(text, style, bg, fg)` - Make a new object for text. The correct use of the method is: `mytext = window.text(text, style, bg, fg)` - you have to create a variable and put the method into it. text is a required argument. All others are not. bg (Background) is the color of the string, for example: `"red"`, fg (text color) - the same. `style` - Important argument, with it you can set the font and size of the text. The value of this argument should look like this: `{'font': 'Arial', 'size': 40}`.

`window.grid(grid_object, row, column)` - All arguments are required. With this method we can put in our window some object (the same text). For example, this shows how to put a text object named hellotext in window - `window.grid(grid_object=hellotext, row=1, column=2)`. Row and column are responsible for the position of the object in the window.

`window.info` - Information about some method (outputs to console)

`window.start` - Start the window, if you want the window to appear at all, be sure to use this method at the **end** of the code.

#### If it doesn't say anything about any method here, you can search for it in the `t2.py` file!
