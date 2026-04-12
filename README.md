# <p align="center"> AM TEACHING MYSELF TO CODE WITH PYTHON AND THIS IS A FOLLOW UP OF MY JOURNEY </p>

While I teach myself to code, I use an app called **CODDY**. This gives me detailed lessons and also motivation to keep my learning journey ahead.

[Link to CODDY](https://link.coddy.tech/bvMS/ref?af_sub2=XQg7AkHDNGew)

This guides me through the basics I should learn and these were my lessons for today;

### LESSON 1 - LEARNING STRINGS⛓️

A letter forexample; 

'A' is a single caracter.

A string(str) is a combination of multiple caracters forexample; 'AAAA'.

In simple terms, a String(str) is a data type that consists of multiple caracters combined together.

To initialize a string, it should either be enclosed in **single** or **double** quotations

         S1 = 'this is a string'
         S2 = "this is a string too"

### LESSON 2 - LEARNING BOOLEAN VALUES🤗

A **BOOLEAN(bool)** is also a data type just like a string is.

A boolean has two possible values, which are;

     ✅ TRUE
     
     ❎ FALSE

**These values only start with a capital letter and stand without quotes🤏**

    Variable_true = True
  
    Variable_false = False

  📛**Booleans are buildinding blocks for creating logic in a programme**

  ### 📌LESSON 3 - NAMING CONVENTIONS IN PYTHON

  Naming convetions are a set of guidelines that developers follow to make their code readable and maintainable.

In **python**, variables are written in snake🐍 case, thats to say; words are separated by underscores.

### LESSON 4 - EMPTY VARIABLES

An **empty variable** is one which has not been assigned a value yet.

In **python**, **None** is a special value that represents the absence of a value.

It exists but there is nothing at all.

         Empty_box = None
         
         (don't include quotes becouse **None** Is not a string in this case)

None is not the same as **0, an empty string" ", or False**. 0, is a number, "" is an empty piece of text, but **None** means there is no value at all.

         score = None      #has not been calculated yet

         name = None        #has not been entered

# DAY 2💪

### LESSON 5 - OPERATORS🎲

These are used to perform calculations on values.📚

**BASIC OPERATORS INCLUDE;**
| OPERATOR | USE            |
|----------|----------------|
| +        | ADDITION       |
| -        | SUBTRACTION    |
| *        | MULTIPLICATION |
| /        | DIVISION       |

**MODULO OPERATOR**

It tells whats left over after dividing one number.➗

         result = dividend % divisor

### Common terms

1. Dividend : The number being divided
2. Divisor : The number that divides the dividend
3. Result : The remainder of the division

         result = 10 % 3
         
                = 1

         ( **This is because 3 goes into 10 only 3 possible times and leaves a remainder of 1. So 1 returns as the answer in this case** )

🤏The modulo function is used to determine whether the value is **even** or **odd**.

**SPECIAL CASE🚑**: when the dividend is smaller than the divisor, the result is the divdidend itself🤗.

                  result = 5 % 8

                           = 5
                  (this is because 8 can't in 5 even once, so 5 remains the answer)
**NOTE**

If a number is **even** , the remainder is **zero**

If a number is **odd** , it leaves a remainder other than **zero**

### ARITHMETIC SHORTCUTS

Python created a cool shortcut for arithmetic operations.

         a = 5
         
         a = a + 3 # a holds 8

We can simplify this by writing += :

         a = 5

         a += 3  # a holds 8

The **+= adds** the value **3 to a**

### OPERATORS AND THERE SHORTCUTS

| Operator | Shortcut|
|----------|---------|
| +        | +=      |
| -        | -=      |
| *        | *=      |
| /        | /=      |
| %        | %=      |

### COMPARISON OPERATORS

These are used to compare between two operands.

### LOGICAL OPERATORS - PART ONE

Logical operators are used to combine conditional statements

Python has three logical operators:

1. and
2. Or
3. not

####**and** -  operator

The and operator returns True if both statements are True.

                  #Create two boolean values

                  X = True

                  Y = True

                  #check if both x and y are True

                  Result = x and y

After executing the above code, result contains;

                  True

If one of the values is **False** , the result will be False.

### 📊 Truth Table

| Condition A | Condition B | A and B |
|------------|------------|--------|
| True       | True       | True   |
| True       | False      | False  |
| False      | True       | False  |
| False      | False      | False  |

### 💻 Example

```python
age = 20
has_id = True

if age >= 18 and has_id:
    print("You are allowed to enter.")
````

---

## 🔹 Decision Making

### 📖 Definition

Decision making allows programs to execute code based on conditions.

### 📊 Statements

| Statement | Purpose                     |
| --------- | --------------------------- |
| if        | Runs if condition is true   |
| elif      | Checks another condition    |
| else      | Runs if all conditions fail |

### 💻 Example

```python
marks = 70

if marks >= 80:
    print("Grade A")
elif marks >= 60:
    print("Grade B")
else:
    print("Grade C")
```

---

## 🔹  Basic Input / Output

### 📖 Definition

* **Input** → Data from user
* **Output** → Data shown to user

### 💻 Example

```python
name = input("Enter your name: ")
print("Hello", name)
```

### ⚠️ Note

`input()` always returns a **string**

### 🔄 Type Conversion

```python
age = int(input("Enter your age: "))
print(age + 5)
```

### 📊 Data Types

| Function | Converts to |
| -------- | ----------- |
| int()    | Integer     |
| float()  | Decimal     |
| str()    | String      |

---

## 🔹Loops

### 📖 Definition

Loops repeat code multiple times.

### 📊 Types of Loops

| Loop  | Description                  |
| ----- | ---------------------------- |
| for   | Iterates over a sequence     |
| while | Runs while condition is true |

---

### 💻 `for` Loop

```python
for i in range(5):
    print(i)
```

---

### 💻 `while` Loop

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

---

### 🔄 Loop Control

| Keyword  | Function        |
| -------- | --------------- |
| break    | Stops loop      |
| continue | Skips iteration |

---

## 🔹  Functions

### 📖 Definition

Functions are reusable blocks of code.

---

### 💻 Basic Function

```python
def greet():
    print("Hello, World!")

greet()
```

---

### 💻 With Parameters

```python
def greet(name):
    print("Hello", name)

greet("Isaac")
```

---

### 💻 With Return Value

```python
def add(a, b):
    return a + b

print(add(3, 4))
```

---

### 📊 Function Structure

| Part       | Meaning          |
| ---------- | ---------------- |
| def        | Defines function |
| name       | Function name    |
| parameters | Inputs           |
| return     | Output           |

---

## 🧪 Exercises

### 🔹 Logical Operators

* Check if a student passed (marks > 50 AND attendance > 75%)
* Create a login system

### 🔹 Decision Making

* Check if number is positive, negative, or zero
* Check voting eligibility

### 🔹 Input / Output

* Ask user for name and age
* Add two numbers from user input

### 🔹 Loops

* Print numbers 1–10
* Print even numbers from 1–20
* Password loop system

### 🔹 Functions

* Function to print your name
* Function to add two numbers
* Function to check even/odd

---

## 🎯 Goals

* ✔️ Master Python basics
* ✔️ Build mini projects
* ✔️ Stay consistent

---

## 📌 Author

👤 **Isaac Kazibwe**
💡 Learning in public & building consistency

---

<p align="center">
  ⭐ Don't forget to star this repo if you like it!
</p>
```


         
                
         

