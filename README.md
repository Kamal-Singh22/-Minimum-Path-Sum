# -Minimum-Path-Sum
Given a grid of size m x n filled with non-negative integers, find a path from the top-left to the bottom-right, which minimizes the sum of all numbers along its path.  You can only move either down or right at any point in time.
Explanation:
Dynamic Programming Table (dp):

dp[i][j] represents the minimum path sum to reach cell (i, j) from the top-left corner.
Base Cases:

The top-left cell is initialized with the grid's top-left value: dp[0][0] = grid[0][0].
Fill the first row and column as they only have one possible path (either right or down).
