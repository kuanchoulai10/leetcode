# [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/description/)


<iframe width="560" height="315" src="https://www.youtube.com/embed/RF_M9tX4Eag?si=BQKFEX8RF5vrc3c9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Three-Stage Reversal** | Navigate to position before `left`, reverse sublist from `left` to `right` using standard reversal, then reconnect the reversed portion | $O(n)$ | $O(1)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/92-reverse-linked-list-ii/92-reverse-linked-list-ii.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/92-reverse-linked-list-ii/92-reverse-linked-list-ii.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/92-reverse-linked-list-ii/92-reverse-linked-list-ii.go"
    ```
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
