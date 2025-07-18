# [1767. Find The Subtasks That Did Not Execute](https://leetcode.com/problems/find-the-subtasks-that-did-not-execute)

<iframe width="560" height="315" src="https://www.youtube.com/embed/NwZAYQSH81k?si=SsFQfdmn3UDwrIqZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

The solution uses a recursive Common Table Expression (CTE) to generate all possible subtasks for each task, then filters out the ones that were executed.

The recursive CTE works in two parts:

1. **Base case**: Start with the original tasks table, which contains each task and its maximum subtask_id
2. **Recursive case**: For each task, generate all subtasks by decrementing the subtask_id until it reaches 1

This creates a complete set of all possible (task_id, subtask_id) pairs. Finally, we use a NOT IN clause to exclude the subtasks that appear in the executed table, leaving only the subtasks that did not execute.

See [Work with recursive CTEs in BigQuery](https://cloud.google.com/bigquery/docs/recursive-ctes) for more details on recursive CTEs.

## Implementation

=== "PostgreSQL"

    ```SQL
    --8<-- "./leetcode/docs/1767-find-the-subtasks-that-did-not-execute/1767-find-the-subtasks-that-did-not-execute.sql"
    ```

=== "Pandas"

    ```python
    --8<-- "./leetcode/docs/xxxx/xxxx.py"
    ```