# [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/cjWnW0hdF1Y?si=nz071fQPELjw4PK3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | Generate all possible subsequences of the array (using recursion or bitmasking). For each subsequence, check if it is strictly increasing by comparing each pair of adjacent elements. Track and return the maximum length among all valid increasing subsequences. | $O(2^n \cdot n)$ There are $2^n$ possible subsequences for an array of length $n$. For each subsequence, checking if it is increasing takes up to $O(n)$ time. So, total time is $O(2^n \cdot n)$. | $O(n)$ The recursion stack or temporary storage for a subsequence can take up to $O(n)$ space. |
| **DP (Bottom-Up)**    | Use a DP array where each entry $dp[i]$ stores the length of the longest increasing subsequence starting at index $i$. Iterate backwards, and for each $i$, check all $j > i$; if $nums[j] > nums[i]$, update $dp[i]$. The answer is the maximum value in $dp$. | $O(n^2)$ For each index, we may check all following indices, leading to $O(n^2)$ total operations. | $O(n)$ The DP array uses $O(n)$ space. |
| **Lorem ipsum dolor** |                            |                     |                      |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/xxxx/xxxx.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
