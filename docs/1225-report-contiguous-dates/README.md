# [1225. Report Contiguous Dates](https://leetcode.com/problems/report-contiguous-dates/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/oh1YtWsN5cw?si=JH1w0PQ41ozJWkIh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary

The solution uses a clever grouping technique to identify contiguous date periods:

1. **Union**: Combine failed and succeeded dates into a single dataset with period state labels
2. **Rank**: Assign sequential ranks to dates within each period state (failed/succeeded)
3. **Group**: Calculate `date - rank * interval '1 day'` - this produces the same value for all contiguous dates
4. **Aggregate**: Group by the calculated value and find min/max dates for each contiguous period

The key insight is that **subtracting the rank from each date creates a constant identifier for contiguous sequences**, making it easy to group and extract date ranges.

## Implementation

=== "PostgreSQL"

    ```sql
    --8<-- "./leetcode/docs/1225-report-contiguous-dates/1225-report-contiguous-dates.sql"
    ```

=== "Pandas"

    ```python
    --8<-- "./leetcode/docs/yyyy/yyyy.py"
    ```
