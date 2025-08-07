# [3. Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/description/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/wiGpQwVHdE0?si=xhVkXkmf8a7zAcFy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

| **Solution Approach** | **Explanation (1-minute)** | **Time Complexity** | **Space Complexity** |
| --------------------- | -------------------------- | ------------------- | -------------------- |
| **Brute Force** | Check all possible substrings and verify each one has unique characters using nested loops. | $O(n^2)$ | $O(min(m,n))$ |
| **Sliding Window (Two Pointers)** | Use left and right pointers with a set to track characters. When duplicate found, shrink window from left until duplicate removed. | $O(n)$ | $O(min(m,n))$ |
| **Sliding Window (Length Tracking)** | Similar approach but tracks substring length directly instead of using two pointers. Removes characters from the beginning when duplicates found. | $O(n)$ | $O(min(m,n))$ |


## Implementation

=== "Python"

    ```python
    --8<-- "./leetcode/docs/3-longest-substring-without-repeating-characters/3-longest-substring-without-repeating-characters.py:sol1"
    ```

    ```python
    --8<-- "./leetcode/docs/3-longest-substring-without-repeating-characters/3-longest-substring-without-repeating-characters.py:sol2"
    ```

=== "JavaScript"

    ```javascript
    --8<-- "./leetcode/docs/yyyy/yyyy.js"
    ```

=== "Go"

    ```go
    --8<-- "./leetcode/docs/zzzz/zzzz.go"
    ```
