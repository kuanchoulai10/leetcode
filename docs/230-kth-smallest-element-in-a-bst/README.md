# [230. Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/5LUXSvjmGCw?si=yKs0ACc9-wx4LzgE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Recursive In-Order** | Use DFS with in-order traversal to visit nodes in sorted order. Count visited nodes and return value when counter equals $k$. | $O(H + k)$ | $O(H)$ |
| **Iterative In-Order** | Use stack to simulate in-order traversal iteratively. Process left subtree, visit node, then right subtree until kth element found. | $O(H + k)$ | $O(H)$ |

**Time Complexity Explanation**: $O(H + k)$ where $H$ is tree height. We traverse at most $H$ nodes to reach leftmost node, then visit $k$ nodes in sorted order.

**Space Complexity Explanation**: $O(H)$ where $H$ is tree height. Recursive approach uses call stack of depth $H$. Iterative approach uses explicit stack that can grow up to $H$ nodes in worst case (skewed tree).


## Implementation

=== "Python"

    ```python title="Recursive"
    --8<-- "./leetcode/docs/230-kth-smallest-element-in-a-bst/230-kth-smallest-element-in-a-bst.py:recursive"
    ```

    ```python title="Iterative"
    --8<-- "./leetcode/docs/230-kth-smallest-element-in-a-bst/230-kth-smallest-element-in-a-bst.py:iterative"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
