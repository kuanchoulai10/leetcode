# [643. Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i)

<iframe width="560" height="315" src="https://www.youtube.com/embed/UdUUnoiLkPg?si=hxi1C5wC70QWcRL9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | Check all possible subarrays of length k and calculate their averages | $O(n*k)$ | $O(1)$ |
| **Sliding Window**    | Maintain a window sum and slide it across the array, updating sum efficiently | $O(n)$ | $O(1)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/643-maximum-average-subarray-i/643-maximum-average-subarray-i.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
    ```
