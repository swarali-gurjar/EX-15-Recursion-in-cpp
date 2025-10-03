# Aim: To study and implement Recursion

## Theory:

Recursion is a programming technique where a function calls itself directly or indirectly to solve a problem.
It breaks a complex problem into smaller subproblems of the same type until a base condition is reached.

**Advantages**

- Simpler and shorter code.

- Natural way to solve problems like factorial, Fibonacci, Tower of Hanoi, tree traversal, etc.

**Disadvantages**

- More memory usage (each call stored in function call stack).

- Slower than iteration due to overhead of function calls.

- Risk of stack overflow if base case is missing or wrong.

**Applications of Recursion**

- Mathematical problems (factorial, Fibonacci, power function).

- Divide and conquer algorithms (Merge Sort, Quick Sort, Binary Search).

- Data structures (Trees, Graphs, Linked Lists).

- Backtracking problems (N-Queens, Sudoku, Maze solving).

## Algorithm: For factorial of a number

**Step 1**: Start

**Step 2**: Read the number x.

**Step 3**: Call the recursive function fact(x)

- If x <= 1, return 1 (base case).

- Else, return x * fact(x - 1) (recursive case).

**Step 4**: Store the result in variable A.

**Step 5** : Display A as the factorial of the number.

**Step 6**: End

## Algorithm: Sum of Integers till n

**Step 1**: Start

**Step 2**: Input the number n.

**Step 3**: Call recursive function add(n).

- Recursive function add(n)

- If n <= 1 → return 1 (base case).

- Else → return n + add(n - 1).

**Step 4**: Store result in variable a.

**Step 5**: Print a as the sum of integers till n.

**Step 6**: Stop.

## Conclusion

In this experiment we learnt that recursion is a technique where a function calls itself to solve a problem by breaking it into smaller subproblems.
We observed that recursion requires a base case to stop execution and a recursive case to continue the process. 
It makes complex problems like factorial, sum of numbers, and string reversal easier to solve with simple code. However, recursion also increases memory usage and may be less efficient than iteration.
