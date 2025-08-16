# [78. Subsets](https://leetcode.com/problems/subsets/description/)

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Iterative (Expanding Subsets)** | Start with empty subset. For each number, create new subsets by copying existing ones and adding the current number. Doubles subset count with each iteration. | $O(n \times 2^n)$ | $O(2^n)$ for output |
| **Recursive (Backtracking)** | Build subsets by making binary choices: include or exclude each element. Recursively explore both paths, adding current subset to result when reaching base case. | $O(n \times 2^n)$ | $O(2^n)$ for output |


## Implementation

=== "Python"

    ```python title="iterative"
    --8<-- "./leetcode/docs/78-subsets/78-subsets.py:iterative"
    ```

    ```python title="recursive"
    --8<-- "./leetcode/docs/78-subsets/78-subsets.py:recursive"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
