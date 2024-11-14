1. What is the difference between a list and a tuple in Python? Give an example of when you would use each.

A list is mutable, it can be modified, stripped, cut and add elements to it. The tuple is similar in structure to the list, it just can't be modified in any shape of form, once it's declared it can't be mutated in any shape or form.

2. Write code to reverse a string without using built-in reverse functions.

``` python
string = 'reversestring'[::-1]
```

3. Explain the difference between `'==' and 'is' in Python with an example.

The difference of `==` is that it compares two values but not it's data types. `is` compares both the values and its data types.

4. What is list comprehension? Provide an example that creates a list of squares of even numbers from 1 to 10.

	According to the definition offered by *W3Schools*: "List comprehension offers a shorter syntax when you want to create a new list based on the values of an existing list."

List comprehension allow for one line syntax and deny the user of creating for loops with conditionals. 

4. Explain the difference between local and global variables. Provide an example.

A local variable is scoped inside a block (Classes, functions , for loops, conditionals), the global variables are declared outside of blocks and are accessible inside classes, functions, for loops and conditionals.

5. What is the difference between append() and extend() for lists? Show examples.

According to the definitions provided by W3Schools, the `append()` method adds an element and the end of the list. Meanwhile the `extend()` method convert to lists in to one, adding all the elements of the `extend()` list at the end of it.



```python
# Examples provided with help of W3School
dog = ['canela', 'sugar', 'snowball']

# Adds at the end of the list the element cinnamon.
dog.append('cinnamon')

animals = ['dog', 'cat', 'squirrel']
owners = ['Rodrigo', 'Michael', 'Seth']

# Extends the list 
animals.extends(owners)

```

6. Write a function that counts the occurrence of each character in a string.

```python
def string_counter() -> None:
    word: str = 'Hello'

    for letter in word:
        print(letter)

string_counter()
```


7. Explain what a lambda function is and provide an example of sorting a list of tuples using lambda.

	 According to the definition provided by W3SChool. The lambda function is a small anonymous function that can take any amount of arguments but only have one expression.

# INTERMEDIATE CONCEPTS

11. Create a class representing a Bank Account with methods for deposit, withdrawal, and balance check. Include proper error handling.

```python
class BankAccount():

	# Defines the methods for deposit, withdrawal and balance check.
    def __init__(self, deposit, withdrawal, balance_check) -> None:
        self.deposit = deposit
        self.withdrawal = withdrawal
        self.balance_check = balance_check
```
