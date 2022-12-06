---
toc: true
layout: post
description: Notes on Booleans and Conditionals
categories: [markdown]
title: Booleans and Conditionals
---

## 3.5 - Boolean Expressions
Here we will focus on: 
- basics of Booleans
- its relationship with binary
- relational operators
- logical operators

### What is a boolean?
A data type with two possible values: true or fals

### Boolean and Binary
So similar yet so different
- Boolean math and binary notation both use the same two ciphers: 1 and 0.
- However, please note that Boolean quantities are restricted to a singular bit
- on the otherhand, binary numbers may be composed of many bits adding up in place-weighted form to any finite value, or size

### Must Knows
- A boolean value is either true or false
- The AP Exam will provide you with a reference sheet with the operators below.
a = b
a =/ b
a > b
a < b
a >= b
a <= b

- A few ways these operators could be used
- equal, not equal, greater than, less than, greater than or equal to, less than or equal to (respectively)

## Logical Operators
These types of operators don't necessarily deal with equivalent/non-equivalent values, but they rather work on operands to produce a singular bollean result
- AND: returns TRUE if the operand around it are TRUE
- OR: returns TRUE if at least one operand is TRUE
- NOT: returns TRUE if the following boolean is FALSE

# Lesson 3.6 - Conditionals
## Focusing on a Selection
*Selection*: uses a condition that evaluates to true or false
Selection determines which part of an algorithm are executed based on a condition being true or false
*Algorithm* is a finite set of instructions that accomplish a specific task

## Conditional Statements
Also known as "if statements"
can be seen as if statements or if blocks
Ex: if (condition)
    [Block of Statements]
can be seen as if else of if else-blocks
Ex: if (condition)
    [Block of Statements]

x=20
y=10
if x > y:
    print("x is greater than y")

x=20
y=10
if x>y:
    print("x is greater than y")
else:
    print("x is not greater than y")

# Lesson 3.7 - nested Conditionals
- Nested conditionals statements consist of conditional statements within other conditional statements
- Utilizes "if else" statements within "if else" satements
- basics of a nested conditional

## Analyzing Code Walkthrough
- Pseuocode to the left, block code to the right
- Approach the problem by going through each condition one at a time
- decide which ones are false to skip and which ones are tru to execute