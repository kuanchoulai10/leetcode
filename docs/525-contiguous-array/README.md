# [525. Contiguous Array](https://leetcode.com/problems/contiguous-array/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/agB1LyObUNE?si=KntHRgUr03ZPmj_R" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | For every subarray, count 0s and 1s; if equal, update max length. | $O(n^2)$ | $O(1)$ |
| **Hash Map (Optimal)** | Use a running count (increment for 1, decrement for 0) and store first occurrence of each count in a hash map. If the same count is seen again, the subarray between indices has equal 0s and 1s. | $O(n)$ | $O(n)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/525-contiguous-array/525-contiguous-array.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
