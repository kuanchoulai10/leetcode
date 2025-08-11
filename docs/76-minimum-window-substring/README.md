# [76. Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/jSto0O4AJbM?si=q7qGp6aqZ9fl7ZNL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | Generate all $O(n^2)$ substrings of `s`. For each substring, count character frequencies and compare with `t`'s requirements. Track the shortest valid substring. | $O(n^2 \times m)$ | $O(m)$ |
| **Sliding Window**    | Use two pointers to maintain a dynamic window. Expand right pointer to include characters until window contains all chars from `t`. Then contract left pointer to minimize window size while maintaining validity. | $O(n + m)$ | $O(m)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/76-minimum-window-substring/76-minimum-window-substring.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
