# C-Day-67-Sum-Divisible-by-3-and-5
# C Day 67 - Sum of Numbers Divisible by 3 and 5

## Description

This program takes multiple numbers from the user and calculates the sum of numbers that are divisible by both 3 and 5.

## Example

```text
Enter how many numbers: 5
Enter number 1: 10
Enter number 2: 15
Enter number 3: 20
Enter number 4: 30
Enter number 5: 7

Sum of numbers divisible by both 3 and 5 = 45
```

## Concepts Used

* `for` loop
* `if` statement
* Modulus operator `%`
* Logical AND operator `&&`
* `scanf()`
* Variables
* Addition

## How It Works

1. The user enters how many numbers they want to check.
2. The program takes each number using a `for` loop.
3. `%` checks whether the number is divisible by 3 and 5.
4. The `&&` operator makes sure both conditions are true.
5. If both conditions are true, the number is added to `sum`.
6. Finally, the program displays the total sum.

## Important Condition

```c
if (number % 3 == 0 && number % 5 == 0)
```

This means the number must be divisible by **both 3 and 5**.

## File Name

`sum_divisible_by_3_and_5.c`

## Goal

The goal of this program is to practice loops, conditions, the modulus operator, logical AND, and calculating a sum based on multiple conditions.
