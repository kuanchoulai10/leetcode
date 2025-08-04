# [257. Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/H2D4HcVZq_g?si=HKAcne9ZUhynHMBK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Recursive DFS**       | Traverse tree recursively, building path by adding nodes and backtracking. When reaching leaf, add complete path to result. Uses implicit call stack. | $O(N)$ | $O(N)$ |
| **Iterative DFS** | Use explicit stack to store `(node, path_string)` pairs. Build path strings as we traverse. When reaching leaf, add path to result. No backtracking needed. | $O(N)$ | $O(N)$ |


## Implementation

=== "Python"

    ```python title="Recursive DFS"
    --8<-- "./leetcode/docs/257-binary-tree-paths/257-binary-tree-paths.py:dfs-resursive"
    ```

    ```python title="Iterative DFS"
    --8<-- "./leetcode/docs/257-binary-tree-paths/257-binary-tree-paths.py:dfs-iterative"
    ```


=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
