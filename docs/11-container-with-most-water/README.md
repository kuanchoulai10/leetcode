# [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water)

<iframe width="560" height="315" src="https://www.youtube.com/embed/UuiTKBwPgAo?si=0SM1D4ZYizD8Rai4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary



| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** | 
|---|---|---|---|
| Brute Force (Nested Loop) | Calculate the area for every possible pair of lines using nested loops. Keep track of the maximum area found. This approach is straightforward but inefficient. | $O(n²)$: Double loop to check all pairs. | $O(1)$: Constant space for variables only. | 
| Two-pointer technique | Use two pointers, one at each end of the array, to represent the lines. Calculate the area and move the pointer with the shorter line inward to potentially find a larger area. Continue until the pointers meet. This approach is efficient and leverages the idea that a shorter line limits the maximum area. | $O(n)$: Single pass as we move pointers inward. | $O(1)$: Constant space with only two pointers. | 



## Implementation

=== Python

    ```python
    --8<-- "./leetcode/docs/11-container-with-most-water/11-container-with-most-water.py"
    ```