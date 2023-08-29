Recursive functions
Description
In this exercises, we will focus on recursive functions.

In each function created throughout these exercises the body of the function must contain a dosctring (a first line with a string explaining what the function does).

Task 1: Sum of Digits
Write a recursive function that takes a non-negative integer as input and returns the sum of its digits.

Example:
sum_of_digits(123) -> 1 + 2 + 3
Return:
6

sum_of_digits(963) -> 9 + 6 + 3
Return:
18


Task 2: Fibonacci Sequence
A Fibonacci sequence is the integer sequence of 0, 1, 1, 2, 3, 5, 8....
The first two terms are 0 and 1. All other terms are obtained by adding the preceding two terms.This means to say the nth term is the sum of (n-1)th and (n-2)th term.

Write a recursive function that takes a non-negative integer n as input and returns the n-th number in the Fibonacci sequence.

Example:
fibonacci(10) -> 0, 1, 1, 2, 3, 5, 8, 13, 21, 34
Output:
Fibonacci sequence:
0
1
1
2
3
5
8
13
21
34

fibonacci(6) -> 0, 1, 1, 2, 3, 5
Output:
Fibonacci sequence:
0
1
1
2
3
5


Task 3: Power Function
Write a recursive function that takes two non-negative integers base and exponent as input and returns the result of base raised to the power of exponent.

Example:
power(2, 3) -> 2 * 2 * 2
Return:
8

power(6, 4) -> 6 * 6 * 6 * 6
Return:
1294

