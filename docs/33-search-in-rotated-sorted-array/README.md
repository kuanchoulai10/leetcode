# [33. Search In Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array)

<iframe width="560" height="315" src="https://www.youtube.com/embed/U8XENwh8Oy8?si=ecpjmUiAtJzTySFa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Modified Binary Search** | Use binary search by comparing middle element with **the last element** to determine **which half is sorted**. Then check if `target` lies in the sorted half to decide search direction. | $O(\log n)$ | $O(1)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/33-search-in-rotated-sorted-array/33-search-in-rotated-sorted-array.py"
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
