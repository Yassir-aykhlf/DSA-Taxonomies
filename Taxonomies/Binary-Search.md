# Binary Search Pattern Taxonomy

> Repeatedly narrow a search interval using value comparisons, local structure, or a monotonic feasibility check — searching indices or the answer itself.

```text
└── Binary Search
    │
    ├── Binary search — classic & boundary (lower/upper bound)
    │   │
    │   ├── "704. Binary Search"
    │   ├── "35. Search Insert Position"
    │   ├── "278. First Bad Version"
    │   ├── "1539. Kth Missing Positive Number"
    │   ├── "2089. Find Target Indices After Sorting Array"
    │   └── "34. Find First and Last Position of Element in Sorted Array"
    │
    ├── Binary search — rotated sorted arrays
    │   │
    │   ├── "33. Search in Rotated Sorted Array"
    │   ├── "153. Find Minimum in Rotated Sorted Array"
    │   ├── "81. Search in Rotated Sorted Array II"
    │   └── "154. Find Minimum in Rotated Sorted Array II"
    │
    ├── Binary search — peaks & mountain arrays
    │   │
    │   ├── "162. Find Peak Element"
    │   ├── "852. Peak Index in a Mountain Array"
    │   └── "1095. Find in Mountain Array"
    │
    ├── Binary search — matrix search & staircase
    │   │
    │   ├── "1337. The K Weakest Rows in a Matrix"
    │   ├── "1351. Count Negative Numbers in a Sorted Matrix"
    │   ├── "74. Search a 2D Matrix"
    │   ├── "240. Search a 2D Matrix II"
    │   └── "302. Smallest Rectangle Enclosing Black Pixels"
    │
    ├── Binary search — parity, k-closest window & arithmetic
    │   │
    │   ├── "69. Sqrt(x)"
    │   ├── "540. Single Element in a Sorted Array"
    │   └── "658. Find K Closest Elements"
    │
    ├── Binary search on the answer — minimize the feasible
    │   │
    │   ├── "875. Koko Eating Bananas"
    │   ├── "1283. Find the Smallest Divisor Given a Threshold"
    │   ├── "1011. Capacity To Ship Packages Within D Days"
    │   ├── "2226. Maximum Candies Allocated to K Children"
    │   ├── "1482. Minimum Number of Days to Make m Bouquets"
    │   ├── "1802. Maximum Value at a Given Index in a Bounded Array"
    │   ├── "3356. Zero Array Transformation II"
    │   └── "2560. House Robber IV"
    │
    ├── Binary search on the answer — minimax & maximin
    │   │
    │   ├── "1552. Magnetic Force Between Two Balls"
    │   ├── "2439. Minimize Maximum of Array"
    │   ├── "410. Split Array Largest Sum"
    │   ├── "2141. Maximum Running Time of N Computers"
    │   ├── "774. Minimize Max Distance to Gas Station"
    │   └── "1231. Divide Chocolate"
    │
    └── Binary search — k-th smallest by counting & median partition
        │
        ├── "719. Find K-th Smallest Pair Distance"
        ├── "4. Median of Two Sorted Arrays"
        ├── "2035. Partition Array Into Two Arrays to Minimize Sum Difference"
        ├── "2040. Kth Smallest Product of Two Sorted Arrays"
        └── "668. Kth Smallest Number in Multiplication Table"
```

> **Related Patterns**:
> - Sorting (ordered values support boundary searches and counting below a threshold)
> - Arrays & Two Pointers (pointer sweeps count qualifying pairs inside an answer search)
> - Greedy (greedy scans test whether a proposed capacity, spacing, or partition is feasible)
> - Heap / Priority Queue (an alternative for selecting k-th elements from ordered sources)
