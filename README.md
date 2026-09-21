# Lab 02: Asymptotic Analysis and Algorithm Running Times

Names:
Kathryn Boidock
Ritesh Ojha
Abishek Dhakal

Work with your Project 1 team to complete the exercises found in `exercises.pdf`. Put your solutions and explanations below. When you are finished, commit and push your repo.

# Part 1:

## Problem 1.1
<!-- Your solution for Problem 1.1 goes here -->
T(n) = 3n^2 + 15n + 100
- 3n^2  is O(n^2) by dropping constants
- 15n is O(n) by dropping constants
- 100 is O(1) by dropping constants
... by Summing is a max rule we have, 3n^2 + 15n + 100 is O(n^2) since n^2 is greater than n and 1.

## Problem 1.2
<!-- Your solution for Problem 1.2 goes here -->
T(n) = 4 * 2^n + 8*n^5
- 4 is O(1) by dropping constants
- 2^n is O(2^n) by exp is faster than polynomial
- 8*n^5 is O(n^k) by dropping constants and Polynomial degree grows faster
... by Summing is a max rule we have, 4 * 2^n + 8*n^5 is O(2^n) since n^n is greater than n^k and 1.

# Part 2:

## Algorithm A
<!-- Your solution for Algorithm A goes here -->
3n^2 + n +2
O(n^2)

## Algorithm B
<!-- Your solution for Algorithm B goes here -->
(2(log2(n) + 1)) + 3
O(nlog(n))

# Part 3:

## Reflection
<!-- Your reflection goes here -->
- The rule of 0(nlogn) is the most unclear to our group.
- Looking over part two Algorithm B, finding the function of n was challenging as we weren't able to fully understand the while loop connecting to the O(nlogn).
- Having more examples like this lab together in class so we feel more confident on our own.