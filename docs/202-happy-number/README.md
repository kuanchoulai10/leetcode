# [202. Happy Number](https://leetcode.com/problems/happy-number/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/ljz85bxOYJ0?si=-5RqUmxlWL4XcTwN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach**         | **Explanation**                                                                 | **Time Complexity** | **Space Complexity** |
|------------------------------|---------------------------------------------------------------------------------|---------------------|----------------------|
| Brute Force with Set         | Each iteration computes sum of squares in $O(\log n)$ time; number of iterations is constant as numbers quickly reduce to a small cycle or 1, so overall $O(\log n)$ time and $O(1)$ space. | $O(\log n)$         | $O(1)$               |
| Floyd's Cycle Detection      | Use slow and fast pointers to detect cycles without extra space.                 | $O(\log n)$         | $O(1)$               |


## Implementation

=== "Python"

    ```python title="Brute Force with Set"
    --8<-- "./leetcode/docs/202-happy-number/202-happy-number.py:set"
    ```

    ```python title="Fast Slow Pointers"
    --8<-- "./leetcode/docs/202-happy-number/202-happy-number.py:fast-slow"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
    ```
