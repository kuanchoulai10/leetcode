# [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures)

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | For each day, iterate through all subsequent days to find the first day with higher temperature | $O(n^2)$ | $O(1)$ |
| **Monotonic Stack**   | Use a decreasing stack to store (index, temperature) pairs. When a warmer day is found, pop all cooler days from stack and calculate their wait times | $O(n)$ | $O(n)$ |

## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/739-daily-temperatures/739-daily-temperatures.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/739-daily-temperatures/739-daily-temperatures.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/739-daily-temperatures/739-daily-temperatures.go"
    ```
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
