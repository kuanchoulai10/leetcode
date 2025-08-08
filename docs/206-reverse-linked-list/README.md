# [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list)

<iframe width="560" height="315" src="https://www.youtube.com/embed/G0_I-ZF0S38?si=awKfBKytCARm9I2i" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Iterative**         | Use three pointers (prev, curr, next) to reverse links while traversing | $O(n)$ | $O(1)$ |
| **Recursive**         | Recursively reverse from tail, then fix current node's links | $O(n)$ | $O(n)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/206-reverse-linked-list/206-reverse-linked-list.py:iterative"
    ```

    ```python
    --8<-- "./leetcode/docs/206-reverse-linked-list/206-reverse-linked-list.py:recursive"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
    ```
