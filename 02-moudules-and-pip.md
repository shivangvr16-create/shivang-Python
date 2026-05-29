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
#

## Example
```
import math

print(math.sqrt(25))
```
# 

## Output:
```
5.0
```
#

## 2. User-Defined Modules

### You can create your own module.

## Example
### File: calculator.py
```
def add(a, b):
    return a + b
```
#

## Main File
```
import calculator

print(calculator.add(5, 3))
```
#

## Output:
```
8
```
#

## Importing Modules
```
Import Entire Module
import math
print(math.pi)
```
#

```
Import Specific Function
from math import sqrt

print(sqrt(64))
```
#

## Import with Alias
```
import numpy as np
```
#

# What is pip?

## pip is Python’s package manager.

## It is used to:

- Install packages
- Update packages
- Remove packages
- Manage external libraries
## Check pip Version
```
pip --version
```
#

## Install a Package
```
pip install requests
```
#

## Upgrade a Package
```
pip install --upgrade requests
```
#

## Remove a Package
```
pip uninstall requests
```
#

## Install Specific Version
```
pip install django==4.2
```
#

## View Installed Packages
```
pip list
```
#

## Save Project Requirements
```
pip freeze > requirements.txt
```
#

### This creates a file containing all installed packages.
#

## Install from requirements.txt
```
pip install -r requirements.txt
```
# 






























































































































































































































































































































































































































































































