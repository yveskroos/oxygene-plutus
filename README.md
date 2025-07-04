# Haskell Programming Exercises

## Table of Contents

1. [Factorial Calculation](#factorial-calculation)
2. [Fibonacci Sequence](#fibonacci-sequence)
3. [List Sum with foldr](#list-sum-with-foldr)
4. [List Product with foldl](#list-product-with-foldl)
5. [List Reversal](#list-reversal)
6. [Element Search](#element-search)
7. [List Length](#list-length)
8. [Even Number Filter](#even-number-filter)
9. [Custom Map Function](#custom-map-function)
10. [Number to Digits](#number-to-digits)

## Factorial Calculation

Implements a recursive function to compute the factorial of a non-negative integer. The factorial of n is the product of all positive integers less than or equal to n, with the base case factorial(0) = 1.

## Fibonacci Sequence

Implements a recursive function to compute the nth Fibonacci number. The Fibonacci sequence is defined as F(0) = 0, F(1) = 1, and F(n) = F(n-1) + F(n-2) for n > 1.

## List Sum with foldr

Implements a function to compute the sum of all elements in a list using the foldr higher-order function. This demonstrates right-associative folding of a list with the addition operator.

## List Product with foldl

Implements a function to compute the product of all elements in a list using the foldl higher-order function. This demonstrates left-associative folding of a list with the multiplication operator.

## List Reversal

Implements a recursive function that reverses the order of elements in a list. The function works by recursively appending the head of the list to the reversed tail.

## Element Search

Implements a recursive function that determines whether a given element exists in a list. The function returns True if the element is found, False otherwise.

## List Length

Implements a recursive function that calculates the length of a list. The function counts each element by recursively processing the tail of the list.

## Even Number Filter

Implements a function that filters all even numbers from a list, returning a new list containing only the even elements. Uses the filter higher-order function with a lambda expression.

## Custom Map Function

Implements a custom version of the map function that applies a given function to each element of a list. This demonstrates how higher-order functions can transform lists.

## Number to Digits

Implements a recursive function that converts a number into a list of its digits. The function works by recursively processing the number by dividing by 10 and collecting remainders.

## Usage

To use these functions, load the Haskell file in GHCi and call the desired functions with appropriate arguments. All functions are pure and have no side effects.

## Requirements

- GHC (Glasgow Haskell Compiler) installed
- Basic understanding of Haskell syntax and recursion
