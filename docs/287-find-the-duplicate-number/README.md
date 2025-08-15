# [287. Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/wjYnzkAhcNk?si=5jgk3R02ooMRvRAv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity**      | **Space Complexity**     |
| --------------------- | -------------------------- | ------------------------ | ------------------------ |
| **Fast-Slow Pointers**| Treat array as linked list where `nums[i]` points to index `nums[i]`. Use Floyd's cycle detection to find where cycle begins (the duplicate). | $O(n)$                   | $O(1)$                   |
| **Binary Search**     | Binary search on value range `[1, n-1]`. For each mid value, count `numbers <= mid`. If `count > mid`, duplicate is in left half, else right half. | $O(n \log n)$            | $O(1)$                   |

## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/287-find-the-duplicate-number/287-find-the-duplicate-number.py:fast-slow-pointers"
    ```

    ```python
    --8<-- "./leetcode/docs/287-find-the-duplicate-number/287-find-the-duplicate-number.py:binary-search"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
