
██╗░░██╗██╗░░░██╗████████╗██╗░░██╗░█████╗░███╗░░██╗
╚██╗██╔╝╚██╗░██╔╝╚══██╔══╝██║░░██║██╔══██╗████╗░██║
░╚███╔╝░░╚████╔╝░░░░██║░░░███████║██║░░██║██╔██╗██║
░██╔██╗░░░╚██╔╝░░░░░██║░░░██╔══██║██║░░██║██║╚████║
██╔╝╚██╗░░░██║░░░░░░██║░░░██║░░██║╚█████╔╝██║░╚███║
╚═╝░░╚═╝░░░╚═╝░░░░░░╚═╝░░░╚═╝░░╚═╝░╚════╝░╚═╝░░╚══╝

# Structures:
> Xythonize.pyd

> UnXythonize.pyd

> README.md

# Requirements: 
Python 3.13

# Usage:

## Step 1: 
Make a Python script near Xythonize.pyd and UnXythonize.pyd
```python
import Xythonize
Xythonize.Xythonize('<file>.py').build_extension()
```
Execute the script to create <file>.xy

## Step 2:
Clean up the .py file
Make another script in the same directory
```python
import UnXythonize #This line is important
import <file> #<file>.xy
#And from here, you can use the functions of <file>.py
```

# Conception:
> Xython is an innovative approach to Python optimization.
 
> By removing unnecessary high-level constructs and whitespace, then doing magic to the optimized code, Xython ensures a leaner execution process. 

> The UnXythonize handles the decompliation and execution, maintaining functionality while enhancing performance.

> Xython leverages Python's power, providing a unique method to potentially increase efficiency in certain scenarios.
