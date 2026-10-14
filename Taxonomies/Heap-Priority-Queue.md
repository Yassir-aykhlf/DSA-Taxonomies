# Heap / Priority Queue Pattern Taxonomy

> Keep the next minimum or maximum ready as candidates change, using heaps to select top-K elements, merge sorted sources, balance streams, and revise greedy choices.

```text
└── Heap / Priority Queue
    │
    ├── Heap — repeatedly pop extreme & reinsert
    │   │
    │   ├── "1046. Last Stone Weight"
    │   ├── "2231. Largest Number After Digit Swaps by Parity"
    │   ├── "3264. Final Array State After K Multiplication Operations I"
    │   ├── "2208. Minimum Operations to Halve Array Sum"
    │   ├── "1167. Minimum Cost to Connect Sticks"
    │   ├── "1792. Maximum Average Pass Ratio"
    │   ├── "2530. Maximal Score After Applying K Operations"
    │   ├── "2233. Maximum Product After K Increments"
    │   ├── "1675. Minimize Deviation in Array"
    │   └── "1354. Construct Target Array With Multiple Sums"
    │
    ├── Top-K / Kth element
    │   │
    │   ├── "2099. Find Subsequence of Length K With the Largest Sum"
    │   ├── "347. Top K Frequent Elements"
    │   ├── "215. Kth Largest Element in an Array"
    │   ├── "378. Kth Smallest Element in a Sorted Matrix"
    │   ├── "692. Top K Frequent Words"
    │   ├── "373. Find K Pairs with Smallest Sums"
    │   ├── "973. K Closest Points to Origin"
    │   └── "1985. Find the Kth Largest Integer in the Array"
    │
    ├── K-way merge with a heap
    │   │
    │   ├── "786. K-th Smallest Prime Fraction"
    │   ├── "355. Design Twitter"
    │   ├── "264. Ugly Number II"
    │   ├── "313. Super Ugly Number"
    │   ├── "23. Merge k Sorted Lists"
    │   ├── "632. Smallest Range Covering Elements from K Lists"
    │   └── "2386. Find the K-Sum of an Array"
    │
    ├── Two heaps & streaming order statistics
    │   │
    │   ├── "703. Kth Largest Element in a Stream"
    │   ├── "295. Find Median from Data Stream"
    │   ├── "480. Sliding Window Median"
    │   └── "1825. Finding MK Average"
    │
    ├── Sort, then sweep a heap by a second key
    │   │
    │   ├── "1834. Single-Threaded CPU"
    │   ├── "2542. Maximum Subsequence Score"
    │   ├── "857. Minimum Cost to Hire K Workers"
    │   └── "1383. Maximum Performance of a Team"
    │
    └── Greedy with a heap of regrets
        │
        ├── "1405. Longest Happy String"
        ├── "1642. Furthest Building You Can Reach"
        ├── "871. Minimum Number of Refueling Stops"
        ├── "502. IPO"
        └── "630. Course Schedule III"
```

> **Related Patterns**:
> - Greedy (priority ordering supplies the best available item and supports replacing earlier choices)
> - Sorting (heap extraction produces the order needed for top-K selection and merging)
> - Binary Search (counting below a candidate value offers another route to k-th element selection)
> - Design (heaps support streaming medians, feed merges, and priority-based APIs)
