# [496. Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/68a1Dc_qVq4?si=ogs8dNok8Zsv0fl-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | Create a mapping of `nums1` elements to indices. For each element in `nums2`, if it exists in `nums1`, scan rightward to find the next greater element using **nested loops**. | $O(n × m)$ | $O(n)$ |
| **Stack**             | Use a **monotonic decreasing stack** to track elements awaiting their next greater element. When a larger element is found, pop from stack and update results for all smaller elements. | $O(n + m)$ | $O(n)$ |

## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/496-next-greater-element-i/496-next-greater-element-i.py:nested-loop"
    ```

    ```python
    --8<-- "./leetcode/docs/496-next-greater-element-i/496-next-greater-element-i.py:stack"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
