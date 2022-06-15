# Interlocking Binary Pairs

Write a function that checks if two non-negative integers make an "interlocking binary pair".

Numbers can be interlocked if their binary representations have no 1's in the same place.
Comparisons are made by bit position, starting from right to left (see the examples below). When representations are of different lengths, the the unmatched left-most bits are ignored.

## Examples

1. a = 9, b = 4

Stacking representations shows how they can interlock. Here, no 1's share any position, so the function returns true.

9 1001 4 100

2. a = 3, b = 6

These representations do not interlock. Finding they both have a 1 in the same position, the function returns false.

3 011 6 110

## TDD Approach

1. Use TDD to create an algorithm that converts decimal to binary
2. Once your Decimal-to-binary converter is written, use TDD to write your function to check whether two decimal numbers interlock.


## Project Templates 

Starter templates for Java, Javascript, and Kotlin can for found in the [C3 Project Template repo](https://github.com/Ingage-Meetup/C3ProjectTemplate)
 
