# [435. Non Overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals)

<iframe width="560" height="315" src="https://www.youtube.com/embed/nONCGxWoUfM?si=_CcQl2nU47fxboau" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | Generate all possible combinations of intervals to remove. For each combination, check if remaining intervals are non-overlapping. Return minimum removals needed. | $O(2^n)$ | $O(n)$ |
| **Greedy (Implemented)** | Sort intervals by start time. Iterate through sorted intervals, when overlap detected, remove the interval with larger end time (keep shorter one). Count total removals. | $O(n log n)$ | $O(1)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/435-non-overlapping-intervals/435-non-overlapping-intervals.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
