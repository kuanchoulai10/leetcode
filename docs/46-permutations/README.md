# [46. Permutations](https://leetcode.com/problems/permutations/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/FZe0UqISmUw?si=tx0_65hvOn77Ft3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | Generate all possible arrangements by trying every element at each position. For each position, iterate through all remaining elements and recursively build permutations. | $O(n! \cdot n)$ | $O(n! \cdot n)$ |
| **Recursive (Backtracking)** | Recursively generate permutations by taking the first element and inserting it at all positions in permutations of remaining elements. Base case returns when only one element remains. | $O(n!)$ | $O(n!)$ |
| **Iterative (Deque)** | Use a deque to iteratively build permutations. For each number, insert it at all possible positions in existing permutations. Start with empty permutation and expand by adding each number at every valid position. | $O(n!)$ | $O(n!)$ |


## Implementation

=== "Python"

    ```python title="Iterative"
    --8<-- "./leetcode/docs/46-permutations/46-permutations.py:iterative"
    ```

    ```python title="Recursive"
    --8<-- "./leetcode/docs/46-permutations/46-permutations.py:recursive"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
