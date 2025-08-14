# [133. Clone Graph](https://leetcode.com/problems/clone-graph/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/mQeF6bN8hMk?si=SpQWbVgUK6S0lFGX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **DFS with HashMap**  | Use DFS to traverse the graph while maintaining a hashmap to store cloned nodes. For each node, create a clone and recursively clone all neighbors, using the hashmap to avoid cycles and duplicate work. | $O(V + E)$ | $O(V)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/133-clone-graph/133-clone-graph.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
