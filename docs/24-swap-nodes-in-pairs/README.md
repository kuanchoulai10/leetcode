# [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/)

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Iterative Pointer Manipulation** | Use a dummy head node and maintain three pointers (prev, curr, next) to iteratively swap adjacent pairs. For each pair, redirect pointers to swap positions. Continue until no more pairs exist. | $O(n)$ | $O(1)$ |

**Example**

`[0(prev) -> 1(curr) -> 2(next) -> 3 -> 4]` --> `[0 -> ==2 -> 1== (prev) -> 3 (curr) -> 4 (next)]` --> `[0 -> 2 -> 1 -> ==4 -> 3==]`

## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/24-swap-nodes-in-pairs/24-swap-nodes-in-pairs.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
