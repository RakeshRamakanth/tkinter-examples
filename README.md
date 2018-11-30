# Tkinter Examples and Screenshots

## Tkinter Button

### Source code example

```python
import tkinter as tk

window = tk.Tk()
window.title("Button Example")
window.geometry("280x50")

btn = tk.Button(window, text="A button", fg="red", bg="yellow")
btn.pack()

window.mainloop()

```

### Screenshot
![Tkinter Button Example](tkinter_button.png "Tkinter Button Example")


## Tkinter Menu and Menubutton

## Tkinter Scale

## Tkinter OptionMenu

## Tkinter Dialogs

## Tkinter Checkbutton

## Tkinter LabelFrame and RationButton

## Tkinter PanedWindow

## Tkinter Canvas

```python
from tkinter import *

canvas_width = 200
canvas_height =200
python_pink = "#FD4BC9"

master = Tk()

w = Canvas(master,
           width=canvas_width,
           height=canvas_height)
w.pack()

points = [100, 140, 110, 110, 140, 100, 110, 90, 100, 60, 90, 90, 60, 100, 90, 110]

w.create_polygon(points, outline=python_pink,
            fill='purple', width=3)

mainloop()

```

### Screenshot
![Tkinter Canvas Example](tkinter-canvas.png "Tkinter Canvas Example")

# Exercise
 - Create a fork of this repository
 - Clone your fork locally
 - Add a source code example and a screenshot to one of the topics
 - Commit and push your changes to your fork
 - Create a pull request for your changes
