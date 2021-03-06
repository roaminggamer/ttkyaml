TtkYaml
=======

TtkYaml is a Python module for constructing ttk (Tkinter) user interfaces 
dynamically from a GUI (Graphical User Interface) dictionary or a yaml file. Using TtkYaml help to build
ttk user interfaces using a programming language independent description file or a GUI 
description dictionary. In some cases using a none programing langage GUI description 
is easier to work with then programing the GUI using a programing language. 

The none programing langage GUI description can be a python dict object, or a file that
can be read and parsed as a dictionary. If pyYAML is installed, the module can use this
module to read and parse the file as a GUI description dict. if the pyYAML module is missing,
users can build a GUI description dict using other methods.

Tkinter is Python's de-facto standard GUI package.

http://wiki.python.org/moin/TkInter

YAML is a human-readable data serialization format.

http://en.wikipedia.org/wiki/YAML


Simple example
--------------
Example GUI build using TtkYaml

![alt exampe on debian](https://raw.github.com/yaacov/ttkyaml/master/examples/simple/deb.png)

![alt example on win6](https://raw.github.com/yaacov/ttkyaml/master/examples/simple/win8.png)
 


