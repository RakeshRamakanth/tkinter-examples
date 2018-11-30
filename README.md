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
![Tkinter Option Example](tkinter_option.png "Tkinter Option Example")

```python
import tkinter as tk

class View(tk.Tk):
    def __init__(self):
        tk.Tk.__init__(self)
        # Fenster
        self.title("Optionmenu-Demo")
        self.geometry('240x80+400+100')
        # Optionmenu
        L = ['Pizza Diavolo','Pizza Margherita','Pizza quattro stagioni']
        self.vS = tk.StringVar(master=self)
        self.vS.set(L[2])
        self.oS = tk.OptionMenu(self,self.vS,*L, command=self.cbOption)
        self.oS = tk.OptionMenu(self, self.vS, *L, command=self.cbOption)
        self.oS.place(x=20,y=20,width=200)

    def cbOption(self,wert):
        print(wert)

v = View()
v.mainloop()
```

## Tkinter Dialogs

## Tkinter Checkbutton

## Tkinter LabelFrame and RationButton

## Tkinter PanedWindow

## Tkinter Canvas

# Exercise
 - Create a fork of this repository
 - Clone your fork locally
 - Add a source code example and a screenshot to one of the topics
 - Commit and push your changes to your fork
 - Create a pull request for your changes
