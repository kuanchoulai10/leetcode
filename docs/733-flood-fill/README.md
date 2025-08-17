# [733. Flood Fill](https://leetcode.com/problems/flood-fill/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/aehEcTEPtCs?si=UlN8N5wjq5ojpMLo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **BFS (Breadth-First Search)** | Use a queue to explore connected pixels level by level. Start from the given pixel, add it to `queue` and `visited` set. For each pixel, change its color and explore all 4 adjacent pixels that have the original color and haven't been visited. Continue until queue is empty. | $O(m \times n)$ | $O(m \times n)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/733-flood-fill/733-flood-fill.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
