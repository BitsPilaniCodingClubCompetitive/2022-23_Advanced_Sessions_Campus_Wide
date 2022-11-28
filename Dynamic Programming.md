# Day 1

## Basic Combinatorics using Dynamic Programming (Optional)
1. Topics you need to cover for internship and placements - Data Structures and techniques.
2. Techniques (overview)
   - [Binary Exponentiation](https://cp-algorithms.com/algebra/binary-exp.html)
   - [Matrix Exponentiation](https://cp-algorithms.com/algebra/binary-exp.html#effective-computation-of-fibonacci-numbers)
2. [Fibonnaci Number](https://cp-algorithms.com/algebra/fibonacci-numbers.html#matrix-form): Finding the $n^{th}$ Fibonacci number, where $1\le n\le 10^{15}$.
3. Find the number of ways to arrange flags on a pole of length $n$. The flags can be of color red, blue and green having length $3, 1, 1$ respectively.


## Introduction to Dynamic Programming techniques
1. $6$ to $7$ problems in Dynamic Programming.
2. Iterative and recursive approach to Dynamic Programming.

### Directed Acyclic Graph
1. The meaning of "Directed", "Acyclic" and "Graph".
2. The meaning of Topological Sorting and its existence. [Video on how to calculate topological sorting (Optional)](https://www.youtube.com/watch?v=cIBFEhD77b4)
3. Visualising Dynamic Programming problems as some DAG.
4. Find the minimum length of shortest path to reach a node starting from node $0$ in a DAG (No code! Should be able to do by hand on paper for any DAG in linear time).


## Questions Covered
### Submissions on leetcode
1. [Counting Bits](https://leetcode.com/problems/counting-bits/).
2. [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/).
### Problems to wonder
1. [Maximum Subarray Problem](https://en.wikipedia.org/wiki/Maximum_subarray_problem) - Solution using Kadane's Algorithm. Task is to derive the Kadane algorithm, where $dp[i]$ was defined in the session. This will be solved in next class.
2. Motivation for recursive approach to Dynamic Programming: In a matrix of size $n\times m$, find the longest increasing path. More details on the problem were covered in the session. This will be solved after few sessions once the basics are covered.

## Homework
1. Do some practice on random DAG and fill the dp array on your own.
2. Should be able to do leetcode easy questions. If not able to do, let me know in next session.


## Plan for next session
1. Submit the code for Kadane's Algorithm after solving on board.
2. Cover easy Dynamic Programming questions of leetcode, ~no submission on spot for these.~ on spot submissions done for some problems.
3. If step 2 completed, take some rest, do one problem on DAG on paper and then start Longest Increasing Subsequence and submit the code on leetode.


## Remarks
Many random things were covered in the session so that you have an idea of what we will be covering in future. If you find the information too much, no need to worry as these will be taken again in future with slow and detailed discussion.


# Day 2

## Questions Covered
### Submitted on Leetcode
1. [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock)
2. [Divisor Game](https://leetcode.com/problems/divisor-game)
3. [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)
4. [Unique Paths](https://leetcode.com/problems/unique-paths/)

### Not Submitted on Leetcode
6. [Jump Game](https://leetcode.com/problems/jump-game/description/)
7. [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)

## Topics Covered
1. Basic game theory for problem: Divisor Game. Optional, no need to cover it.
2. Kadane's Algorithm Derivation.
3. An example of 2D dp and the submission on leetcode.
4. LIS

## Homework
1. Revise the questions covered.
2. Leetcode Medium Questions.


# Day 3
## Topics to cover
1. General Trees (Basics)
2. Edit Distance
3. Knapsack (both cases)

## Questions Solved
1. [Edit Distance](https://leetcode.com/problems/edit-distance/)
2. [Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/)
3. [Is Same Tree](https://leetcode.com/problems/same-tree/)
4. [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
5. [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/)
6. [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/)
7. [Path Sum](https://leetcode.com/problems/path-sum/)

## Work to do
1. Easy questions of binary tree and possibly general trees.
2. Medium problems of dp and problems related to edit-distance and knapsack.

# Day 4
## Topics Covered
1. Chain Matrix Multiplication.
2. Shortest Path from a node in acyclic graph.
3. Recursive approach to dp.
   - *What’s the best naming prefix for a global variable?* `//` 

## Questions Solved
1. [Atcoder - Educational DP Contest](https://atcoder.jp/contests/dp/tasks)
   1. [Frog 1](https://atcoder.jp/contests/dp/tasks/dp_a)
   2. [Frog 2](https://atcoder.jp/contests/dp/tasks/dp_b)
   3. [Vacation](https://atcoder.jp/contests/dp/tasks/dp_c)
   4. [Knapsack 1](https://atcoder.jp/contests/dp/tasks/dp_d)
   5. [Knapsack 2](https://atcoder.jp/contests/dp/tasks/dp_e)
   6. [LCS](https://atcoder.jp/contests/dp/tasks/dp_f)
   7. [Longest Path](https://atcoder.jp/contests/dp/tasks/dp_g)
   8. [Grid 1](https://atcoder.jp/contests/dp/tasks/dp_h)
2. [Dynamic Programming Book](https://drive.google.com/file/d/1niwm8nsmuZiswxUQZsvPjtEnEHRbRc44/view?usp=sharing)
   1. Question 6.4
   2. Question 6.6
3. [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/)
4. [Word Break](https://leetcode.com/problems/word-break)
   - [Simple Solution](https://leetcode.com/problems/word-break/solutions/2752032/c-dp-0ms-100-faster/)
   - The time complexity of above solution is $O(n^3)$ instead of $O(n^2)$. Can you tell why?
   - What if you used `set` instead of `unordered_set` to store dictionary words? What if `vector` is used to store dictionary words?

## Work to do
1. Solve the questions on leetcode or any other websites as much as you can. Dynamic Programming is almost completed and you should be able to solve questions on your own or reason about the approach after reading the solution without mugging it up.
2. Submit the codes on atcoder that were discussed in the class.
3. Reason about how recursive code works and can there be problems using recursive approach? *Hint*: The answer is not `global variables`. Assume stack size of $1$ $mb$.
4. Read about `queue` of STL - the functions and how to use it. It will be used in BFS of graph theory.

## Plan for next session
1. Bellman Ford.
2. Travelling Salesman Problem.
3. Graph Theory - Basic Nomenclature and iteration techniques.

# Day 5 (Skipped)
Read about Bellman Ford and Travelling Salesman Problem from the book.

# References
1. [Dynamic Programming Book](https://drive.google.com/file/d/1niwm8nsmuZiswxUQZsvPjtEnEHRbRc44/view?usp=sharing)
