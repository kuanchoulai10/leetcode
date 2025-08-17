# [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/6ZnyEApgFYg?si=kNbOeRI7sabGfkSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **BFS with Queue**    | Use a queue to traverse nodes level by level. For each level, process all current nodes in queue, add their children for next level, and collect values. | $O(n)$ | $O(w)$ where $w$ is max width |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/102-binary-tree-level-order-traversal/102-binary-tree-level-order-traversal.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
