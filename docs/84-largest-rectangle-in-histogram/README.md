# 84. Largest Rectangle in Histogram

<iframe width="560" height="315" src="https://www.youtube.com/embed/zx5Sw9130L0?si=difN3DrU3LulISx0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Stack-based (Monotonic Stack)** | Use a stack to track indices and heights. When current height is smaller than stack top, pop elements and calculate area using the popped height. The width is determined by the distance between current index and the updated index from popped elements. This ensures we find the maximum rectangle for each height efficiently by maintaining increasing heights in the stack. | $O(n)$ | $O(n)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/84-largest-rectangle-in-histogram/84-largest-rectangle-in-histogram.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
