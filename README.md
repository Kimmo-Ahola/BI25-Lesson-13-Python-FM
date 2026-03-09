# Exercises: Loops, Lists, and Dictionaries

1. Exercise 1

fruits = ["apple", "banana", "cherry"]

Print each fruit on a separate line.

---
2. Exercise 2

numbers = [2, 4, 6, 8, 10]

Calculate the total sum using a loop and print it.

---
3. Exercise 3

numbers = [1, 2, 3, 4]

Multiply each number by 2 and print the new numbers.

---
4. Exercise 4

Create a list of squares from 1 to n.
Expected result if n = 5: [1, 4, 9, 16, 25].

Extend the function so it now works for negative n as well. In this case the results should be negative.

Expected result if n = -5: [-1, -4, -9, -16, -25]

---
5. Exercise 5

names = ["Alice", "Bob", "Charlie"]

Use this code to ask the user (you) for an input and check for the result in the list.
```python
user_input = input("Give me a name: ") # we get a prompt in the terminal that asks for input. Write a string and press enter.
```
Ask the user for a name and print "Found!" if it is in the list. Print "Not Found :(" if it is not in the list.

---
6. Exercise 6

Given the string:

text = "PythonProgramming"

Extract the substring "Python" using slicing.

---
7. Exercise 7

Given the same string:

text = "PythonProgramming"

Extract the substring "Programming" using slicing.

---
8. Exercise 8

Given the string:

text = "PythonProgramming"

Extract every second character from the string.

---
9. Exercise 9

Given the string:

text = "PythonProgramming"

Reverse the string using slicing.

---
10. Exercise 10

Given the string:

text = "PythonProgramming"

Extract the substring "thonProg" using slicing.

---
11. Exercise 11

Given the list:

numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

Extract the sublist [3, 4, 5, 6] using slicing.

---
12. Exercise 12

Given the same list:

numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

Extract all even-indexed elements.

---
13. Exercise 13

Given the same list:

numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

Reverse the list using slicing.

---
14. Exercise 14

Given the same list:

numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

Extract [1, 3, 5, 7] using slicing.

---
15. Exercise 15

Given the same list:

numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

Extract [9, 7, 5, 3] using slicing.

---

16. Exercise 16

grades = {"Alice": 90, "Bob": 85, "Charlie": 92}

Print each student’s name.

---
17. Exercise 17

Print each student’s grade from the dictionary above.

---
18. Exercise 18

Print statements like "Alice has the grade 90" for each student in the dictionary. Use a loop and an f string to print the result.

---
19. Exercise 19

Increase every student’s grade by 5 points in the dictionary.

---

# Exercises – Strings and Lists

1. First and last characters

Write a function that prints the first and last character of a string.
Example: "Python" → "P", "n"

---
2. Count vowels in a string

Write a function that counts how many vowels (a, e, i, o, u) are in a string using a loop.
Example: "hello world" → 3

---
3. Every second character

Write a function that returns every second character of a string using slicing.
Example: "abcdefgh" → "bdfh"

---
4. Check palindrome

Write a function that checks if a string is a palindrome (same forwards and backwards) using slicing.
Example: "radar" → True, "hello" → False

---
5. Sum numbers in a list

Write a function that takes a list of numbers and returns their sum using a loop.
Example: [1, 2, 3, 4] → 10

---
6. Reverse a list

Write a function that reverses a list using slicing.
Example: [1,2,3,4] → [4,3,2,1]

---
7. Extract sublist

Write a function that returns a slice of a list from index start to end (not inclusive).
Example: [10,20,30,40,50], start=1, end=4 → [20,30,40]

---
8. Remove every second element

Write a function that removes every second element from a list using slicing.
Example: [1,2,3,4,5,6] → [1,3,5]

---
9. Find max and min in a list

Write a function that returns the maximum and minimum values from a list using a loop.
Example: [3, 7, 2, 9, 4] → (9, 2)

---

# Exercises - Regex


> You can load the text files by using
```python
with open("sample1.txt", "r") as f:
    text = f.read()
```

1. Extract emails ending with .se

2. Extract all dates (YYYY-MM-DD) that are in the 1900s or 2000s

3. Extract all prices ending with SEK
prices = re.findall(r'\b\d{1,3}(?:,\d{2})?SEK\b', text)

4. Extract all phone numbers that start with swedish country code (+46) and are of correct length

5. Extract all URLs ending with .se. Modern urls start with https://.


6. Extract capitalized words (like names and places)


# Harder questions
1. Exercise 1 - Count Occurences

fruits = ["apple", "banana", "apple", "cherry", "banana", "apple"]

Count how many times each fruit appears and store it in a dictionary.
Expected output: {"apple": 3, "banana": 2, "cherry": 1}

---
2. Exercise 2 – Group by first letter

Given this list:

words = ["apple", "banana", "pear", "kiwi", "strawberry"]

Create a dictionary where keys are the first letters of each word and values are lists of words starting with that letter.

Expected output:

{"a": ["apple"], "b": ["banana"], "p": ["pear"], "k": ["kiwi"], "s": ["strawberry"]}

---
3. Exercise 3 – Filter dictionary

Given this dictionary:

grades = {"Alice": 85, "Bob": 92, "Charlie": 78, "Diana": 95}

Create a new dictionary containing only the students who scored 90 or more. Use a loop for this and create a new dictionary.

Expected output:

{"Bob": 92, "Diana": 95}

---
4. Exercise 4 – Find the longest word

Given this list:

words = ["apple", "banana", "pear", "kiwi", "strawberry"]

Find the longest word in the list.

Expected output:

"strawberry"
