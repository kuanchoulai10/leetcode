# [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/gBTe7lFR3vc?si=AUJlMpBgO8u6ceiF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Hash Set**          | Store visited nodes in a set. If we encounter a node already in the set, there's a cycle. | $O(n)$ | $O(n)$ |
| **Two Pointers (Floyd's Cycle Detection)** | Use slow and fast pointers. Slow moves 1 step, fast moves 2 steps. If they meet, there's a cycle. | $O(n)$ | $O(1)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/141-linked-list-cycle/141-linked-list-cycle.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/141-linked-list-cycle/141-linked-list-cycle.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/141-linked-list-cycle/141-linked-list-cycle.go"
    ```
    ```
