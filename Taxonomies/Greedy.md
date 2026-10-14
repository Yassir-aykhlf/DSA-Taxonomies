# Greedy Pattern Taxonomy

> Commit to locally justified choices, using sorted order, frequency counts, or running state — an exchange argument or invariant explains why the final result is correct.

```text
└── Greedy
    │
    ├── Greedy — reachability (jump games & covering)
    │   │
    │   ├── "45. Jump Game II"
    │   ├── "55. Jump Game"
    │   ├── "1306. Jump Game III"
    │   ├── "1024. Video Stitching"
    │   └── "1326. Minimum Number of Taps to Open to Water a Garden"
    │
    ├── Single-pass running aggregate
    │   │
    │   ├── "169. Majority Element"
    │   ├── "414. Third Maximum Number"
    │   ├── "485. Max Consecutive Ones"
    │   ├── "628. Maximum Product of Three Numbers"
    │   ├── "53. Maximum Subarray"
    │   └── "134. Gas Station"
    │
    ├── Greedy — arrangement by frequency
    │   │
    │   ├── "621. Task Scheduler"
    │   ├── "767. Reorganize String"
    │   ├── "1054. Distant Barcodes"
    │   ├── "451. Sort Characters By Frequency"
    │   ├── "2384. Largest Palindromic Number"
    │   ├── "3016. Minimum Number of Pushes to Type Word II"
    │   └── "1121. Divide Array Into Increasing Sequences"
    │
    ├── Greedy — sort then local decision
    │   │
    │   ├── "1200. Minimum Absolute Difference"
    │   ├── "1029. Two City Scheduling"
    │   ├── "1481. Least Number of Unique Integers after K Removals"
    │   ├── "846. Hand of Straights"
    │   ├── "2592. Maximize Greatness of an Array"
    │   ├── "406. Queue Reconstruction by Height"
    │   ├── "3207. Maximum Points After Enemy Battles"
    │   ├── "2554. Maximum Number of Integers to Choose From a Range I"
    │   └── "2551. Put Marbles in Bags"
    │
    ├── Greedy — two-pass / adjacent-transition reconciliation
    │   │
    │   ├── "845. Longest Mountain in Array"
    │   ├── "581. Shortest Unsorted Continuous Subarray"
    │   ├── "135. Candy"
    │   └── "1526. Minimum Number of Increments on Subarrays to Form a Target Array"
    │
    ├── Greedy — exchange / median to equalize cost
    │   │
    │   ├── "2448. Minimum Cost to Make Array Equal"
    │   ├── "2561. Rearranging Fruits"
    │   └── "296. Best Meeting Point"
    │
    ├── Greedy — two-pointer matching after sorting
    │   │
    │   ├── "455. Assign Cookies"
    │   ├── "881. Boats to Save People"
    │   └── "870. Advantage Shuffle"
    │
    └── Greedy — scanning with running state
        │
        ├── "860. Lemonade Change"
        ├── "1903. Largest Odd Number in String"
        ├── "605. Can Place Flowers"
        ├── "763. Partition Labels"
        ├── "678. Valid Parenthesis String"
        ├── "1899. Merge Triplets to Form Target Triplet"
        ├── "2340. Minimum Adjacent Swaps to Make a Valid Array"
        ├── "849. Maximize Distance to Closest Person"
        ├── "670. Maximum Swap"
        └── "2366. Minimum Replacements to Sort the Array"
```

> **Related Patterns**:
> - Sorting (a suitable key exposes the order in which local choices are safe)
> - Arrays & Two Pointers (sorted endpoints guide matching and pairing decisions)
> - Heap / Priority Queue (repeatedly supplies the best available candidate for scheduling or arrangement)
> - Dynamic Programming (tracks multiple states when one local choice is insufficient)
