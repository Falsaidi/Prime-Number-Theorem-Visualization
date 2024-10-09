# Prime-Theorem
Visualization of a developing prime number theorem.

This prime theorem was developed by Nicole Molin. The basic idea is to separate all numbers into columns, organized by the sum of the number's digits (ie. the first column is 1, 10, 19, 28, etc., second column would be 2, 11, 20, 29, etc.). By analyzing these columns, it can be found that from any prime number in any column, the distance to the next prime is 18x. This can be extended to all other prime numbers in that same column, meaning that |x - y| = 18x with x and y being primes within the same column.

The purpose of my program is to display a graph showing this pattern in various ways to help find new discoveries related to it. The program uses Matplotlib to display the graph.
