# PYTHON PROGRAMMING MODULE 04
## NAME : PREETHI D
## REGISTER NUMBER: 212224040250

# EXP 01 -  Classes and Objects in Python: Calculate the Area of a Circle

##  Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

##  Program
```
import math

class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle is:", area)

radius = float(input("Enter the radius of the circle: "))
obj = cse()
obj.mech(radius)

```

## Output
![image](https://github.com/user-attachments/assets/c38ed67e-77cd-45f2-9b2e-11081be587d1)

## Result
Therefore the given Python program has been executed successfully and the output has been verified.

# EXP 02- Dictionary Operations in Python: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

merged = dict1.copy()
merged.update(dict2)

print("Merged Dictionary:", merged)

```

## Output
![image](https://github.com/user-attachments/assets/b35ad22d-9c8a-41f0-8c73-011741cb7809)

## Result
Therefore the given Python proram has been executed successfully and the output has been verified.
