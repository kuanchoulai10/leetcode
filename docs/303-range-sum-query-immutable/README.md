# [303. Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/2pndAmo_sMA?si=BbM70FBLpe64_Vmu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | For each query, iterate through the range `[left, right]` and sum all elements. Simple but inefficient for multiple queries. | Init: $O(1)$, Query: $O(n)$ | $O(1)$ |
| **Prefix Sum (Optimal)** | Precompute cumulative sums in constructor. Each query becomes $O(1)$ by subtracting prefix sums. | Init: $O(n)$, Query: $O(1)$ | $O(n)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/303-range-sum-query-immutable/303-range-sum-query-immutable.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
