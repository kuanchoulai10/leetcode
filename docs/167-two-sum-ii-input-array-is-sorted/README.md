# [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/cQ1Oz4ckceM?si=QtsQUpW4JzJmo8hO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary



| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** | 
|---|---|---|---|
| **Naive Approach (Nested Loop)** | Use two nested loops to try every possible pair of numbers. For each pair, check if their sum matches the target. Return the indices if a match is found. | **O(n²)**: The outer loop iterates over each element, and the inner loop checks all elements after it, resulting in quadratic time. | **O(1)**: Constant space since no extra data structures are used. | 
| **Two-pointer technique** | Use two pointers on the sorted array, one starting at the beginning and the other at the end. Check the sum and adjust the pointers accordingly to find the solution in one pass. | **O(n)**: Linear scan as the two pointers converge towards the solution. | **O(1)**: Only pointers are used, with no extra space. | 


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/167-two-sum-ii-input-array-is-sorted/167-two-sum-ii-input-array-is-sorted.py"
    ```