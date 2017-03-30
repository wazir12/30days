# Day 26: Nested Logic

Task 

Your local library needs your help! Given the expected and actual return dates for a library book, create a program that calculates the fine (if any). The fee structure is as follows:

If the book is returned on or before the expected return date, no fine will be charged (i.e.: fine = 0

If the book is returned after the expected return day but still within the same calendar month and year as the expected return date, fine = 15 Hackos * num days late

If the book is returned after the expected return month but still within the same calendar year as the expected return date, the fine = 500 Hackos * num months late

If the book is returned after the calendar year in which it was expected, there is a fixed fine of 10000 Hackos

Input Format

The first line contains 3 space-separated integers denoting the respective day, month, and year on which the book was actually returned. 

The second line contains 3 space-separated integers denoting the respective day, month, and year on which the book was expected to be returned (due date).

Constraints

Output Format

Print a single integer denoting the library fine for the book received as input.

Sample Input

9 6 2015
6 6 2015

Sample Output

45
