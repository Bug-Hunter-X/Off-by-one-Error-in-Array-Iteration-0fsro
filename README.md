# Off-by-one Error in Array Iteration

This repository demonstrates a common yet subtle error in Java programming: the off-by-one error when iterating over arrays.

## The Bug

The provided Java code attempts to populate an array with even numbers. The loop condition, however, uses `i <= arr.length`, leading to an `ArrayIndexOutOfBoundsException`. Arrays in Java are zero-indexed, so the last valid index is `arr.length - 1`.

## The Solution

The solution modifies the for loop condition to `i < arr.length`, ensuring that the loop iterates correctly up to the last valid index of the array.

## How to run the code

1. Clone this repository.
2. Compile and run the Java files using a Java compiler (like javac and java).