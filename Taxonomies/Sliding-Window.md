# Sliding Window Pattern Taxonomy

> Move two boundaries over a contiguous span, updating sums or frequencies as elements enter and leave to optimize window length or count valid subarrays.

```text
└── Sliding Window
    │
    ├── Variable window — longest under a constraint
    │   │
    │   ├── "3. Longest Substring Without Repeating Characters"
    │   ├── "1004. Max Consecutive Ones III"
    │   ├── "1695. Maximum Erasure Value"
    │   ├── "1658. Minimum Operations to Reduce X to Zero"
    │   └── "1493. Longest Subarray of 1's After Deleting One Element"
    │
    ├── Variable window — frequency / replacement budget
    │   │
    │   ├── "424. Longest Repeating Character Replacement"
    │   ├── "904. Fruit Into Baskets"
    │   ├── "1234. Replace the Substring for Balanced String"
    │   └── "1838. Frequency of the Most Frequent Element"
    │
    ├── Variable window — shortest covering a requirement
    │   │
    │   ├── "209. Minimum Size Subarray Sum"
    │   ├── "76. Minimum Window Substring"
    │   └── "727. Minimum Window Subsequence"
    │
    ├── Fixed-size sliding window
    │   │
    │   ├── "643. Maximum Average Subarray I"
    │   ├── "1176. Diet Plan Performance"
    │   ├── "219. Contains Duplicate II"
    │   ├── "567. Permutation in String"
    │   ├── "438. Find All Anagrams in a String"
    │   ├── "1888. Minimum Number of Flips to Make the Binary String Alternating"
    │   └── "30. Substring with Concatenation of All Words"
    │
    └── Counting subarrays with a window
        │
        ├── "713. Subarray Product Less Than K"
        ├── "1248. Count Number of Nice Subarrays"
        ├── "930. Binary Subarrays With Sum"
        ├── "1358. Number of Substrings Containing All Three Characters"
        ├── "992. Subarrays with K Different Integers"
        ├── "2444. Count Subarrays With Fixed Bounds"
        ├── "2302. Count Subarrays With Score Less Than K"
        └── "3329. Count Substrings With K-Frequency Characters II"
```

> **Related Patterns**:
> - Arrays & Two Pointers (window boundaries are two pointers advancing through the same sequence)
> - Hashing & Grouping (frequency maps track duplicates, distinct values, and required counts)
> - Prefix Sums (prefix aggregates offer another route to some subarray-sum problems)
> - Stack & Queue (monotonic deques maintain the minimum or maximum inside a moving window)
