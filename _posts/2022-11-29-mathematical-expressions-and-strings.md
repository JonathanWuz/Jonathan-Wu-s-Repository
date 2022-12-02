---
toc: true
layout: post
description: Notes on Mathematical Expressions and Strings
categories: [markdown]
title: Mathematical Expression and Strings
---

# Mathematical Expression and Strings

## Algorithms
An algorithm: a set of instructions that can accomplish a specific task

### An Algorithm has three 
1. Sequencing: Algorithms do taks in the order of specification
2. Selection: Helps choose two different outcomes based off a decision
3. Iteration: If a conditions is true, then the code can repeat

### Algorithms can be Represented in Two Ways
1.*Flowcharts*: Use shapes and arrows to represent the steps of an algorithm

A*flowcharts*
use shapes and arrows to represent the steps of an algorithm
- different shapes represent different functions
- For example, the circle represents the start and end whereas an arrow represents a relationship between relative shapes. There is also a rectangle, parallelogram, and diamond which have their specific functions.
- Pseudocode: A blend of human language and coding format

## Arithmetic Operations
Arithmetic operations exist in most programming languages

### Basic Operations
Subtraction:
- represented by "-"
Ex: num1 = 2 - 1

Addition:
- represented by "+"
Ex: num1 = 2 +1

Multiplication
- represented by "*"
Ex: num1 = 2 * 1

Division
- represented by "/"
num1 = 2/1

Getting the Remainder
represented by "MOD" (% in python)
num1 = 5 % 2

## Different Uses
Items can be numbers or variables
Example:
num1 = 10
num2 = num1 -25
num3 = 100 * num1
num4 = num1 / num2
num5 = 9 % num4

## Order of Operations
Arithmetic operations in programming are performed in the same order as operations in mathematics:
- operations in parentheses should be done first
- division and multiplication should be done before addition and subtraction
- modulus works similar to multiplication and division
Example: Evaluate num1
num1 = 9 % 2 * (8 - 2) + 8 / (6 - 4)
num1 = 10.0

## Variables

### Different Ways Values are Stored in Variables
1. Numerical value stored in a variable
2. Value of another variable stored in a variable
3. result of an operation stored in a variable
4. Result of a procedure call stored in a variable

score = 0
score = newScore
score = newScore + 2
avgScore = allscores(20, 60, 80)

### Sequencing is Important!
Changing the order of the steps changes the overall outcome, since every time the value assigned to a variable is changed, it overrides the last value which was assigned to the same variable. That is why it is important to track the value of variables, especially in code where the value is constantly changing.

num1 = 2
num2 = 4
num3 = 6
num1 = num2 + num3
num2 = num1 + num3
Vs.
num1 = 2
num2 = 4
num3 = 6
num2 = num1 + num3
num1 = num2 + num3

### Tracking Variables
Tracking variables is a common question found on AP exams and is an important thing to keep in mind when writing any code. If the value of your variables changes a lot, not accounting for these changes can result in an unwanted outcome.

var1 = 9
var2 = 7
var3 = 2
print(var1)
print(var2)
print(var3)
