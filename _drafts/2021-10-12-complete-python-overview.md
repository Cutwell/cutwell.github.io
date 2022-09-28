---
layout: post
title: Procedural content generation in a constrained non-dynamic system.
categories: [Game Design, Python]
---

![python logo](/images/2021-10-12-complete-python-overview/1.png "python logo")

# A complete* guide to Python 3.10
*Terms and conditions apply.

What is the problem with Python guides? Well, for the beginner, absolutely nothing. But emphasis on _beginner_. Many advanced programmers, having learnt a language or two, will know that fundamentally all high level programming languages are the same. Functions, for-loops, conditionals and variables are largely all conceptually identical among most popular programming languages, all that changes is the flair / flavour of each language (the syntax expected to produce these simple concepts) and whatever built-in functionality the language offers to make it useful for a particular niche problem.

Therefore, instead of suffering through simple tutorials to learn basic language syntax, programmers will often jump to [https://learnxinyminutes.com/](https://learnxinyminutes.com/) to view a cheat-sheet of all the basic syntax and functionality they need to get into programming.

What this guide seeks to provide is a more in-depth (and hopefully, friendly) look into the core mechanics of Python (as of [3.10](https://pythoninsider.blogspot.com/2021/10/python-3100-is-available.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+PythonInsider+%28Python+Insider%29)), offering the depth of "learnxinyminutes" but the commentary of a proper tutorial.

---
## Chapter 01: Variables and types

### Defining variables
Programming languages can be characterised by wether they have a "strict" or "dynamic" typing system. In Python, variables are all dynamically typed and are mutable, meaning variables can be reassigned at any point to any data type.

```python
# For example:
x = 10
x = "some string"
```

### What are types
Python types (string, list, integer, etc.) are all classes, inheriting from the generic 


### Methods for strings
https://www.tutorialspoint.com/built-in-string-methods-in-python
| Method | arguments | description |
| :----: | :-------: | :---------: |
| "".capitalise | | capitalises the first character of the string | 
| "".center | width, fillchar=' ' | returns a padded string centered to a total width of columns | 
| "".count | str, beg=0, end=len(string) | returns occurences of substring within string, or subsection of string | 
| "".decode | encoding='UTF-8', errors='strict' | decodes the string using a codec | 
| "".encode | encoding='UTF-8', errors='strict' | encodes a string using a codec | 
| "".endswith | suffix, beg=0, end=len(string) | returns True if string or substring ends with a substring, false if not | 
| "".expandtabs | tabsize=8 | converts tabs (\t) to multiple spaces | 
| "".isalnum |  | returns True if the string contains only alphanumeric characters, else False (if empty or failing condition) | 
| "".isalpha |  | returns True if the string contains only alphabetic characters, else False (if empty or failing condition) | 
| "".isdigit |  | returns True if the string contains only digits, else False (if empty or failing condition) | 
| "".islower |  | returns True if the string contains only lowercase characters, else False (if empty or failing condition) | 
| "".isnumeric |  | returns True if the string contains only numeric characters, else False (if empty or failing condition) | 
| "".isspace |  | returns True if the string contains only whitespace characters, else False (if empty or failing condition) | 
| "".istitle |  | returns True if string is titlecased, false otherwise | 
| "".isupper |  | returns True if the string contains only capitalised characters, else False (if empty or failing condition) | 
| "".join | seq | concatenates elements in 'seq' as strings to the string, with seperator character | 
| "".lower |  | converts all uppercase letters to lowercase | 
| "".lstrip | width, fillchar=' ' | 
| "".ljust | width, fillchar=' ' | 
| "".maketrans |  | 
| "".replace | old, new [, max] | 
| "".rjust | width, fillchar=' ' | 
| "".rfind | str, beg=0, end=len(string) | 
| "".rstrip | | 
| "".split | str=' ', num=string.count(str) | 
| "".splitlines | num=string.count('\n') | 
| "".startswith | str, beg=0, end=len(string) | 
| "".strip | \[chars\] | 
| "".swapcase |  | 
| "".title |  | 
| "".translate | table, deletechars="" | 
| "".upper |  | 
| "".zfill | width | 
| "".isdecimal |  | 

### Functions for strings
| Method | arguments | description |
| :----: | :-------: | :---------: |
| len | string | returns the length of a given string | 
| max | str | returns the greatest value character | 
| min | str | returns the smallest value character | 