# Python Tkinter Template

## 01Template -> Tkinter with class
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
![image](.../Templates/01Template/img01.png)


Simple overview of use/purpose.

## Description

An in-depth paragraph about your project and overview of use.

## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program

```bash
$ python3 main.py
```
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)