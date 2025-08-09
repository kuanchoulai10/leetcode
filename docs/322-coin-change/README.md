# [322. Coin Change](https://leetcode.com/problems/coin-change/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/H9bfqozjoqs?si=oTvGyNp47QWg9iTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Dynamic Programming (Bottom-up)** | Build solution from amount 0 to target amount. For each amount, try all coins and take minimum coins needed. Use `dp[i]` to store minimum coins for amount `i`. | O(amount × coins) | O(amount) |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/322-coin-change/322-coin-change.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
