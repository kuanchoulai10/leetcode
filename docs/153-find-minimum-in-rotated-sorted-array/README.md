# [153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/nIVW4P8b1VA?si=asmjDXFMWdE1HlYC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Binary Search**     | Use binary search to find the minimum element. First check if array is not rotated (`nums[0] < nums[-1]`). Otherwise, find the element where both left and right neighbors are larger. Compare middle element with the last element to determine which half contains the minimum. | $O(\log n)$ | $O(1)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/153-find-minimum-in-rotated-sorted-array/153-find-minimum-in-rotated-sorted-array.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
