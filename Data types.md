**Data types in python:**

1. *String* 
These values are words and sentences. They need to be enclosed by " ".
**For example**
        text = "Hello World"
        print(text) #Output: Hello World 
        Here, "Hello World" is an value of string data type passed to variable text. 

2. *int*
These values are numbers. They need to be simple numbers.
**For example**
    number = 20;
    print(number) # Output: 20

3. *float*
Like int, they are numeric data types. However, they are in decimal format.
**For example**
    number = 20.7;
    print(number) # Output:20.7

4. *Complex Numbers*
Python supports complex numbers, represented as a + bj, where a is the real part and b is the imaginary part.

**For example**
    z = 3 + 4j
    print(z.real)  # Output: 3.0
    print(z.imag)  # Output: 4.0

5. *boolean*
These data types are either true or false. They are used in conditional statement (if-else).

**For example**
    a=True;
    if a: 
        print ("Condition is True")
    
    else:
        print(" Conditon is False")

#output: Condition is True

6. *List*
An ordered collection of items that can be of different data types. Lists are mutable (modifiable).

**For example**

fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']

7. *Tuple*
Similar to a list, but immutable (cannot be modified after creation).

**For example**

coordinates = (10, 20)
print(coordinates[0])  # Output: 10

8. *Dictionary (dict)*
Stores data as key-value pairs. Keys are unique, and values can be of any data type.

**For example**

person = {"name": "Alice", "age": 25}
print(person["name"])  # Output: Alice

9. *Set*
An unordered collection of unique items. Useful for operations like union and intersection.

**For example**

numbers = {1, 2, 3, 3, 4}
print(numbers)  # Output: {1, 2, 3, 4}

10. *Frozenset*

An immutable version of a set.

**For example**

frozen = frozenset([1, 2, 3])
print(frozen)  # Output: frozenset({1, 2, 3})

11. *Bytes*
 A sequence of bytes, often used for binary data. Immutable.

**For example**

data = b"hello"
print(data[0])  # Output: 104 (ASCII value of 'h')

12. *Bytearray*
Similar to bytes, but mutable.

**For Example**

data = bytearray(b"hello")
data[0] = 72  # Change 'h' to 'H'
print(data)  # Output: b'Hello'

13. *Range*

Represents a sequence of numbers, commonly used in loops.

**For example**

for i in range(5):
    print(i)  # Outputs: 0, 1, 2, 3, 4

14. *NoneType*

Represents the absence of a value or a null value.

**For example**

value = None
if value is None:
    print("Value is None")  # Output: Value is None

15. *Enumerations (Enum)*

Used to define symbolic names for a set of values.

**For example**

from enum import Enum

class Color(Enum):
    RED = 1
    GREEN = 2
    BLUE = 3

print(Color.RED)  # Output: Color.RED

16. *User-Defined Classes/Objects*

Custom data types created using classes.

**For example**
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

my_car = Car("Toyota", "Corolla")
print(my_car.brand)  # Output: Toyota

    