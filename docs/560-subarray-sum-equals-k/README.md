# [560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/fFVZt-6sgyo?si=KNISfgTU97gnzCED" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)**                                                                 | **Time Complexity**       | **Space Complexity**      |
| --------------------- | ------------------------------------------------------------------------------------------ | ------------------------- | ------------------------- |
| **Brute Force**       | Check all possible subarrays and calculate their sums.                                     | $O(n^2)$: Two nested loops | $O(1)$: No extra space used |
| **Prefix Sum + Hashmap** | Use a hashmap to store prefix sums and their counts. Check for complement in each step. | $O(n)$: Single iteration  | $O(n)$: Hashmap stores prefix sums |

## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/560-subarray-sum-equals-k/560-subarray-sum-equals-k.py"
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
