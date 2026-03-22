# Python data types
<img width="928" height="423" alt="image" src="https://github.com/user-attachments/assets/ad80e0df-f369-4b36-ad07-face8e651188" />

## Let's start --
### 1 - Numeric

#### I - Integer
#### II - Float
#### III - Complex Numbers
## I - Integers 
### Definition
#### Integers are ofen called number or a decimal
### For example :-
## You can run this code in python for seeing examples
```
a = 13
b = 16
c = 20
d = 20.9
print(a , b , c , d)
```

### Output will be :-
<img width="651" height="240" alt="image" src="https://github.com/user-attachments/assets/826e5588-7cf5-439d-b919-46ae74989db1" />

```
13 16 20 20.9
```
## II - Float
### Definition
#### A float is a floating-point number, meaning it can store fractional values (numbers with decimals) as well as very large or very small numbers using scientific notation
### For example :-
## You can this code in python for seeing examples
```
x = 10       
y = float(x) 
print(y)     

z = float("3.5")
print(z)     
```
### Output will be :-
<img width="679" height="251" alt="image" src="https://github.com/user-attachments/assets/1c60acde-b55f-424b-ad63-4eed9edbfeab" />

```
10.0
3.5
```
## III - Complex Number
### Definition 
#### A complex number is a number made up of two components: a real number and an imaginary number, expressed together as 𝑎 + 𝑏𝑖
### For example :-
## You can run this code in python for seeing examples 
```
z = 2 + 3j   # complex number
print(z)
```
### Output will be :-
```
(2+3j)
```
## 2 - Boolaen
### Defenition
#### A Boolean is a data type that can only be True or False, used to represent logical conditions
### For Example :-
## You can run this code in python for seeing examples
```
x = 5
y = 10

print(x < y)
print(x == y)
```
### Output will be :-
```
True
False
```
## 3 - Dictionary
### Definiton
#### A dictionary is an unordered, mutable collection where each item is stored as a pair:

#### Key → a unique identifier (must be immutable, like strings, numbers, or tuples).

#### Value → the data associated with that key (can be any type).

### 🔑 Key Points
#### Defined using curly braces {}.

#### Keys must be unique; values can be duplicated.

#### Dictionaries are optimized for fast lookups by key.
### For example :-
## You can run this code in python for seeing the examples
```
student = {
    "name": "Amit",
    "age": 21,
    "course": "Computer Science"
}

print(student["name"])   
print(student["age"])
```
### Output will be
```
Amit
21
```
## 4 - Set
### Definition
#### A set is a mutable collection that stores multiple items, but does not allow duplicates. It is commonly used when you need to keep track of distinct values
### For example :-
## You can run this code in python to seeing examples
```
fruits = {"apple", "banana", "orange", "apple"}  

print(fruits)  
a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))        
print(a.intersection(b))
```
### Output will be
```
{'apple', 'banana', 'orange'}
{1, 2, 3, 4, 5}
{3}
```
## 5 - Sequence Type
#### I -  String
#### II -  Tuple
#### III -  Range
#### IV -  List
## I - String
### Definition

#### A string is an immutable ordered collection of characters used to store and manipulate text. It can include letters, numbers, symbols, and even spaces.

#### 🔑 Key Points
#### Strings are written inside single quotes ' ', double quotes " ", or triple quotes ''' ''' / """ """ (for multi-line text).

#### Strings are immutable, meaning once created, they cannot be changed directly.

#### Each character in a string has an index (position), starting from 0
### For example :-
## You can run this code in python for seeing examples
```
# Creating strings
name = "Alice"
greeting = 'Hello'
multiline = """This is
a multi-line string."""

# Accessing characters
print(name[0])  
print(name[1:4]) 
```
### Output will be :-
```
A
lic
```
## II - Tuple
### Definition
#### A tuple is a sequence of items, similar to a list, but cannot be changed after creation (immutable). It is used to group related data together.

#### 🔑 Key Points
#### Defined using parentheses ( ) or simply commas.

#### Elements can be of different data types (integers, strings, floats, etc.).

#### Tuples are ordered, meaning elements have a fixed position and can be accessed by index.

#### Immutable → once created, you cannot add, remove, or modify elements
### For example :-
## You can run this code in python for seeing examples
```
# Creating a tuple
student = ("Amit", 21, "Computer Science")

print(student[0])   
print(student[1])  

# Tuple without parentheses
numbers = 1, 2, 3
print(numbers)      
```
### Output will be :-
```
Amit
 21
(1, 2, 3)
```
## III - Range
### Definition
#### A range is an immutable sequence of integers defined by a start, stop, and step value. It generates numbers on demand rather than storing them all at once, making it memory-efficient.

#### 🔑 Key Points
#### Created using the range() function.
### For example :-
## You can run this code in python for seeing examples
```
# Basic usage
for i in range(5):
    print(i)

# With start and stop
for i in range(2, 7):
    print(i)

# With step
for i in range(1, 10, 2):
    print(i)
```
### Output will be :-
```
0 1 2 3 4
2 3 4 5 6
1 3 5 7 9
```
## IV - List
### Definition
#### A list is a sequence of items that can store multiple values, including different data types, in a single variable. Unlike tuples, lists are mutable, meaning you can change, add, or remove elements after creation.

#### 🔑 Key Points
#### Defined using square brackets [ ].
 
#### Elements can be of mixed types (integers, strings, floats, even other lists).

#### Ordered → elements maintain their position and can be accessed by index.

#### Mutable → you can modify the list after creation.
### For example :-
## You can run this code in python for seeing examples
```
# Creating a list
fruits = ["apple", "banana", "orange"]

print(fruits[0])   
print(fruits[1])   

# Modifying the list
fruits.append("grape")   # Add element
fruits.remove("banana")  # Remove element
print(fruits)            
```
### Output will be :-
```
apple
banana
['apple', 'orange', 'grape']
```
## 5 - None
### Defenition
#### None is a data type of its own (NoneType) and is used to indicate that something is empty, not set, or has no meaningful value.

#### 🔑 Key Points
#### None is not the same as 0, False, or an empty string/list.

#### It is often used as a default return value for functions that don’t explicitly return anything.

#### You can check for None using the is operator.
### For example :-
## You can run this code in python for seeing examples
```
# Example 1: Function without return
def greet():
    print("Hello")

result = greet()
print(result)  

# Example 2: Checking None
x = None
if x is None:
    print("x has no value")  
```
### Output will be :-
```
None
x has no value
```
# We have finished data types !!!!!!!!!! 
# Hurrah !!!










