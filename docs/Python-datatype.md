# Python data types
<img width="928" height="423" alt="image" src="https://github.com/user-attachments/assets/ad80e0df-f369-4b36-ad07-face8e651188" />

## Let's start --
## Numeric

* Integer
* Float
* Complex Numbers
## Integers 
### Definition
#### Integers are ofen called number or a decimal
### For example :-
## Run this code in python to show examples
```
a = 13
b = 16
c = 20
d = 20.9
print("a , b , c , d")
```
### Output will be :-
```
13 16 20 20.9
```
## Float
### Definition
#### A float is a floating-point number, meaning it can store fractional values (numbers with decimals) as well as very large or very small numbers using scientific notation
### For example :-
## Run this code in python for showing examples
```
x = 10       
y = float(x) 
print(y)     

z = float("3.5")
print(z)     
```
### Output will be :-
```
10.0
3.5
```
## Complex Number
### Definition 
#### A complex number is a number made up of two components: a real number and an imaginary number, expressed together as 𝑎 + 𝑏𝑖
### For example :-
## Run this code in python for showing examples 
```
z = 2 + 3j   # complex number
print(z)
```
### Output will be :-
```
(2+3j)
```
## Boolaen
### Defenition
#### A Boolean is a data type that can only be True or False, used to represent logical conditions
### For Example :-
## Run this code in python for showing examples
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
## Dictionary
### Definiton
#### A dictionary is an unordered, mutable collection where each item is stored as a pair:

#### Key → a unique identifier (must be immutable, like strings, numbers, or tuples).

#### Value → the data associated with that key (can be any type).

### 🔑 Key Points
#### Defined using curly braces {}.

#### Keys must be unique; values can be duplicated.

#### Dictionaries are optimized for fast lookups by key.
### For example :-
## run this code in python for showing the examples
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
## Set
### Definition
#### A set is a mutable collection that stores multiple items, but does not allow duplicates. It is commonly used when you need to keep track of distinct values
### For example :-
## Run this code in python to showing examples
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
## Sequence Type
* String
* Tuple
* Range
* List
## String
### Definition

#### A string is an immutable ordered collection of characters used to store and manipulate text. It can include letters, numbers, symbols, and even spaces.

#### 🔑 Key Points
#### Strings are written inside single quotes ' ', double quotes " ", or triple quotes ''' ''' / """ """ (for multi-line text).

#### Strings are immutable, meaning once created, they cannot be changed directly.

#### Each character in a string has an index (position), starting from 0
### For example :-
## Run this code in python for showing examples
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
## Tuple
### Definition
#### A tuple is a sequence of items, similar to a list, but cannot be changed after creation (immutable). It is used to group related data together.

#### 🔑 Key Points
#### Defined using parentheses ( ) or simply commas.

#### Elements can be of different data types (integers, strings, floats, etc.).

#### Tuples are ordered, meaning elements have a fixed position and can be accessed by index.

#### Immutable → once created, you cannot add, remove, or modify elements
### For example :-
## Run this code in python for showing examples
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










