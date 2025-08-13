# [2300. Successful Pairs Of Spells And Potions](https://leetcode.com/problems/successful-pairs-of-spells-and-potions)

<iframe width="560" height="315" src="https://www.youtube.com/embed/OKnm5oyAhWg?si=mk7xsnbrx6A70jOh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | For each spell, check every potion to see if their product meets the success threshold. Count valid pairs by iterating through all spell-potion combinations. | $O(n \cdot m)$ - Check each of $n$ spells against each of $m$ potions | $O(1)$ - Only store counters and result array |
| **Binary Search** | Sort potions array, then for each spell find the minimum potion strength needed. Use binary search to find the first valid potion, then count remaining potions. | $O(m \log m + n \log m)$ (Sort potions once, then binary search for each spell) | $O(1)$ (Constant extra space excluding output array) |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/2300-successful-pairs-of-spells-and-potions/2300-successful-pairs-of-spells-and-potions.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
