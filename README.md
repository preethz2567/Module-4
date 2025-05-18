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

# EXP 03- Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

##  Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## Program
```
my_dict = {
    'France': 'Paris',
    'Japan': 'Tokyo',
    'India': 'New Delhi',
    'Brazil': 'Brasilia',
    'Canada': 'Ottawa'
}

sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("Original dictionary:", my_dict)
print("\nDictionary sorted by keys:", sorted_by_keys)
print("\nDictionary sorted by values:", sorted_by_values)

```

## Sample Output
![image](https://github.com/user-attachments/assets/2d293de6-b6e0-4786-94a2-ae5cbbbfd226)

## Result
Therefore the given Python program has been executed successfully and the output has been verified.

# EXP 04- Exception Handling in Python: Avoiding Index Errors

## Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

##  Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## Program
```
list1 = [10, 20, 30, 40]

try:
    print("Element at index 5:", list1[5])
except IndexError:
    print("You're out of list range")

```

## Output
![image](https://github.com/user-attachments/assets/4455f496-02fc-4190-8293-ec66ba629452)

## Result
Therefore the given Pyhon program has been executed successfully and the output has been verified.

#  EXP 05 -File Handling in Python: Count Lines Not Starting with 'T'

##  Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

##  Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

##  Program
```
with open('story.txt', 'w') as f:
    f.write("The stars shine brightly tonight.\n")
    f.write("Some lines start with T.\n")
    f.write("Others don't.\n")

count = 0
with open('story.txt', 'r') as file:
    for line in file:
        if not line.startswith('T'):
            count += 1

print("Lines not starting with 'T':", count)

```
## Output
![image](https://github.com/user-attachments/assets/dbb3d75c-2162-4068-928f-aa5e044e09f8)

## Result
Therefore thr givrn Python program has been executed successfully and the output has been verified.
