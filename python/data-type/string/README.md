# String
String is an ordered sequence of characters. It is non-mutable datatype.


## 1. Slicing

We can extract substring from a string using indexes.
### Syntax:
str_var[start_index:end_index:step]

### Example

**Declare a variable 'name' that stores a string value**

name = "Python" 
**Retrieving first character in a string**
print(name[0]) 
**Prints 'P'**

**Retrieving last character in a string**

print(name[-1])
print(name[5])

**Prints 'n' , -1 represents last character value in the string**

## 2. Slicing String

### Syntax:
 string_var[start_index: end_index: step]

**By default: start_index = 0, end_index = length of string and step = 1**

### Example
**Retrieving 'ython'**

print(name[1:])

**Retrieving 'yth'**

print(name[1:4])

**Retrieving 'Pto'**

print(name[::2])

**Reverse a string**

print(name[::-1])

### Output

P

n

n

ython

yth

Pto

nohtyP

## 2. Case Manipulation

We can convert all characters in string to lower, upper or title case.

### Example

**Declare a variable 'name' that stores a string value**

name = "John brown"

**String to lower case**

print(name.lower())

**String to upper case**

print(name.upper())

**String to title case**

print(name.title())

### Output
john brown

JOHN BROWN

John Brown

## 3. Split String

We can break string using a separator character(s).
### Syntax:
string_var.split("separator")
### Example

**Declare a variable 'name' that stores a string value**

name = "John brown"
words = name.split(" ")

**String to lower case**

print(words)

### Output
['John', 'brown']

## 4. Format String

We can format strings.

### Example

**Declare a variable 'name' that stores a string value**

name = "John Brown"

age = 25

sentence = f"{name} is {age} years old."

print(sentence)

### Output
John Brown is 25 years old.

## 5. String Comparison

We can compare strings using equality operator. String comparison is case sensitive.

### Example

**Declare variables 'name1' and 'name2' that stores a string value**

name1 = "John Brown"

name2 = "john brown"

print(name1 == name2)

print(name1.lower() == name2.lower())

### Output
False

True

## 6. Mask String

### Example

credit_card = "1234567812345"

last_four_char = credit_card[-4:]

masked_credit_card = "x" \* (len(credit_card)-4) + last_four_char

print(masked_credit_card )

### Output

xxxxxxxxx2345
