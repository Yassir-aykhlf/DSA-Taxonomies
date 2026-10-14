# Sorting Pattern Taxonomy

> Put data in a useful order with comparisons, buckets, or in-place rearrangement — then use that order to simplify searches, range queries, and pair counting.

```text
└── Sorting
    │
    ├── Custom comparator / key sorting
    │   │
    │   ├── "1636. Sort Array by Increasing Frequency"
    │   ├── "953. Verifying an Alien Dictionary"
    │   ├── "179. Largest Number"
    │   ├── "937. Reorder Data in Log Files"
    │   ├── "791. Custom Sort String"
    │   └── "1366. Rank Teams by Votes"
    │
    ├── Implement a sorting algorithm
    │   │
    │   ├── "148. Sort List"
    │   ├── "912. Sort an Array"
    │   └── "969. Pancake Sorting"
    │
    ├── Non-comparison sorts & in-place reordering
    │   │
    │   ├── "164. Maximum Gap"
    │   ├── "274. H-Index"
    │   ├── "324. Wiggle Sort II"
    │   └── "539. Minimum Time Difference"
    │
    ├── Sort, then binary-search or prefix-sum queries
    │   │
    │   ├── "2389. Longest Subsequence With Limited Sum"
    │   ├── "1385. Find the Distance Value Between Two Arrays"
    │   ├── "2602. Minimum Operations to Make All Array Elements Equal"
    │   ├── "1300. Sum of Mutated Array Closest to Target"
    │   ├── "1508. Range Sum of Sorted Subarray Sums"
    │   └── "1889. Minimum Space Wasted From Packaging"
    │
    └── Sort, then count pairs with two pointers
        │
        ├── "1099. Two Sum Less Than K"
        ├── "2824. Count Pairs Whose Sum is Less than Target"
        ├── "2563. Count the Number of Fair Pairs"
        └── "1885. Count Pairs in Two Arrays"
```

> **Related Patterns**:
> - Arrays & Two Pointers (sorted values guide pair-counting sweeps and merge steps)
> - Binary Search (sorting creates the order needed for boundary and threshold queries)
> - Prefix Sums (cumulative sums over sorted values support cost and capacity queries)
> - Linked List (merge sort orders nodes by relinking sorted runs)
