# Prefix Sums Pattern Taxonomy

> Precompute prefix and suffix aggregates to reuse work across ranges, with hash maps for matching states and difference arrays for recording range updates.

```text
└── Prefix Sums
    │
    ├── Prefix sum + hashmap (subarray sums)
    │   │
    │   ├── "525. Contiguous Array"
    │   ├── "560. Subarray Sum Equals K"
    │   ├── "523. Continuous Subarray Sum"
    │   └── "974. Subarray Sums Divisible by K"
    │
    ├── Prefix XOR & parity bitmasks + hashmap
    │   │
    │   ├── "1371. Find the Longest Substring Containing Vowels in Even Counts"
    │   ├── "1915. Number of Wonderful Substrings"
    │   └── "1442. Count Triplets That Can Form Two Arrays of Equal XOR"
    │
    ├── Prefix/suffix aggregates & difference arrays
    │   │
    │   ├── "724. Find Pivot Index"
    │   ├── "303. Range Sum Query - Immutable"
    │   ├── "238. Product of Array Except Self"
    │   ├── "370. Range Addition"
    │   ├── "1109. Corporate Flight Bookings"
    │   ├── "3355. Zero Array Transformation I"
    │   └── "995. Minimum Number of K Consecutive Bit Flips"
    │
    └── 2D prefix sums — submatrix aggregates
        │
        ├── "304. Range Sum Query 2D - Immutable"
        ├── "1314. Matrix Block Sum"
        └── "1292. Maximum Side Length of a Square with Sum Less than or Equal to Threshold"
```

> **Related Patterns**:
> - Hashing & Grouping (maps count or locate earlier prefix states)
> - Bit Manipulation (prefix XOR and parity masks encode even/odd character counts)
> - Sliding Window (a moving span offers another route to some contiguous-range problems)
> - Advanced Structures (Fenwick and segment trees extend range queries to mutable data)
