# [1. Two Sum](https://leetcode.com/problems/two-sum/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/KLlXCFG5TnA?si=Wv8pTCyf2WIJyz0g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach**                    | **Explanation**                                                                                                                               | **Time Complexity**                                                 | **Space Complexity**                                                |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Brute Force (Nested Loop)**            | Check every possible pair of numbers to see if they add up to the target. This approach is straightforward but slow.                          | $O(n^2)$: We need to check all pairs, which requires a nested loop. | $O(1)$: Constant space as we don't need extra storage.              |
| **Two-pointer technique (Sorted Array)** | Sort the array and use two pointers (one at the start, one at the end). Move pointers based on the sum comparison to target.                  | $O(n\log n)$: Sorting takes O(n log n), and a linear scan is O(n).  | $O(1)$: Only pointers, no extra data structures needed.             |
| **Hash Map (One-pass)**                  | Traverse the array while storing each number in a hash map. For each number, check if the complement (target - number) is already in the map. | $O(n)$: Single pass through the array to check and store elements.  | $O(n)$: Extra space for storing up to `n` elements in the hash map. |

## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/1-two-sum/1-two-sum.py"
    ```