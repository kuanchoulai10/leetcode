# [374. Guess Number Higher Or Lower](https://leetcode.com/problems/guess-number-higher-or-lower)

<iframe width="560" height="315" src="https://www.youtube.com/embed/xW4QsTtaCa4?si=GNdrUyRn_n-8QSB9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force**       | Start from 1, incrementally guess each number up to `n` until the correct number is found | $O(n)$ | $O(1)$ |
| **Binary Search**     | Repeatedly guess the middle of the current range and narrow the range based on feedback from the guess API | $O(\log n)$ | $O(1)$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/374-guess-number-higher-or-lower/374-guess-number-higher-or-lower.py"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
