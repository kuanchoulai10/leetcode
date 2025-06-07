# [15. 3Sum](https://leetcode.com/problems/3sum/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/jzZsG8n2R9A?si=Hul4XVnvqHHsmJUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| Solution Approach       | Explanation                                                                                                                                                     | Time Complexity                                                                 | Space Complexity                                                   |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| Brute Force             | Iterate through all triplets and check if their sum is zero. This approach is straightforward but inefficient for large arrays.                                 | $O(n^3)$ - three nested loops iterate through the array                         | $O(1)$ - no extra space used beyond input storage                  |
| Two Pointers            | Sort the array first, then for each element, use two pointers from both ends to find pairs that sum to the target. Skip duplicates to avoid redundant triplets. | $O(n^2)$ - outer loop iterates $n$ times, inner two-pointer search takes $O(n)$ | $O(1)$ - only uses constant extra space for pointers and variables |
| HashSet without Sorting | Convert 3Sum to 2Sum for each element. Use sets for deduplication and avoid processing duplicate first elements. No array modification required.                | $O(n^2)$ - outer loop iterates $n$ times, inner 2Sum takes $O(n)$               | $O(n)$ - uses sets for storing seen elements and results           |

## Implementation


=== "Python"

    ```python
    --8<-- "./leetcode/docs/15-3sum/15-3sum.py"
    ```