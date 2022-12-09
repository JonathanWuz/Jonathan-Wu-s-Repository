---
toc: true
layout: post
description: Notes on Lists and Iterations
categories: [markdown]
title: Lists and Iterations
---

# Lists and Iterations

## Lists

### What are lists?
*Lists*: a sequence of variables
- we can use lists to store multiple items into one variable
- used to store collections of data
- changeable, ordered, allow duplicates

**List examples in Python, JavaScript, and Pseudocode**

fruits = ["apple", "grape", "strawberry"]
print (fruits)

const fruits = ["apple", "grape", "strawberry"];

fruits <- [apple, grape, strawberry]

More List examples

brands = ["nike", "adidas", "underarmour"]
numbers = [1, 2, 3, 4, 5]
truefalse = [True, False, true]

**Lists are just one of four collection data types in Python**
- *Tuple*: collection that is ordered, unchangeable, allows duplicates
- *Set*: collection that is unordered, unchangeable, doesn't allow duplicates
- *Dictionary*: collection that is ordered, changeable, doesn't allow duplicates

**Terms**
- *Index*: a term used to sort data in order to reference to an element in a list (allows for duplicates)
- *Elements*: the values in the list assigned to an index

fruits = ["apple", "grape", "strawberry"]
index = 1

print (fruits[index])

### Methods in Lists
append() - adds elements to the end of the list
insert() - adds element at given position
reverse() - reverses the lsit order
count() - returns the amount of elements with the specified value
clear() - removes the elements from the list

**Try this**
- Determine the output of the code segment
words <- "old", "car", "unusual", "new", "bold", "far", "away"
index <- 1
FOR EACH word IN words
    If LEN(word) = 3
        REMOVE(words, index)
    ELSE
        index <- index + 1
Display(words)
This will output "unusual", "bold", "away"

## Iteration
### First, what not to do
Iteration is important for your time and sanity
Coding a lot of blocks indivisually takes a lot of unnecessary time, how can we shorten this time?

**Iteration**
Iteration is the repetition of a process or utterance applied to the result or taken from a previous statement. There's a lot of types of iteration though, what to use?
How do we apply iteration to lists?

Some methods include using a "for loop", using a "for loop and range()", using a "while loop", and using comprehension

Lists, tuples, dictionaries, and sets are iterable objects. They are the 'containers' that store the data to iterate

Each of these containers are able to iterate with the iter() command.

There are 2 types of iteration: define and indefinite. Define iteration clarifies how many times the loop is going to run, while indefinite specifies a condition that must be met

for variable in iterable:
    statement()

**Iterator? Iterable? Iteration?**