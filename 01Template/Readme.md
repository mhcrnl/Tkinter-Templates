# Tkinter Template with Class

```python
#!/usr/bin/python3
# -*- coding: utf-8 -*-
# FILE: __main__.py
# RUN : python3 __main__.py
# ----------------------------------------------------BEGIN file
import tkinter as tk
from tkinter import ttk

class Application(tk.Frame):
    def __init__(self, master, *args, **kwargs):
        super().__init__(master, *args, **kwargs)
        self.pack()

        self.master.geometry("650x450")
        self.master.title("Tkinter Template with Class")

        self.create_widgets()

    def create_widgets(self):
        pass

    def callBack(self):
        pass

def main():
    root = tk.Tk()
    app = Application(master=root)#Inheritance
    app.mainloop()

if __name__ == "__main__":
    main()
# ------------------------------------------------------END file
```

![image](img01.png)