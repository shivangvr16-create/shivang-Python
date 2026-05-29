# Python Modules and pip

## What is a Module in Python?

### A module is a Python file (.py) that contains reusable code such as:

- Functions
- Classes
- Variables
- Constants

### Modules help organize large projects into smaller reusable files.
#

# Why Use Modules?

## Benefits

- Reusable code
- Cleaner structure
- Easier debugging
- Faster development
- Better teamwork
#

# Types of Modules
## 1. Built-in Modules

### Python already includes many modules.

## Examples
```
Module                  	Use

math                      Mathematical operations

random	                  Random numbers

os	                      Operating system tasks

time	                    Time handling

sys	                      System-related functions
```
## Example
```
import math

print(math.sqrt(25))
```
## Output:
```
5.0
```
## 2. User-Defined Modules

### You can create your own module.

## Example
### File: calculator.py
```
def add(a, b):
    return a + b
```
## Main File
```
import calculator

print(calculator.add(5, 3))
```
## Output:
```
8
```
## Importing Modules
```
Import Entire Module
import math
print(math.pi)
```
```
Import Specific Function
from math import sqrt

print(sqrt(64))
```
## Import with Alias
```
import numpy as np
```

































































































































































































































































































































































































































































































