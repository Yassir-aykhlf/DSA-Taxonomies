# Dynamic Programming Pattern Taxonomy

> Define states for overlapping subproblems and combine their answers through a recurrence, storing results with memoization or tabulation to avoid solving the same state twice.

```text
└── Dynamic Programming
    │
    ├── 1D linear DP — additive recurrence
    │   │
    │   ├── "70. Climbing Stairs"
    │   ├── "1137. N-th Tribonacci Number"
    │   ├── "509. Fibonacci Number"
    │   ├── "198. House Robber"
    │   ├── "91. Decode Ways"
    │   ├── "2466. Count Ways To Build Good Strings"
    │   ├── "2327. Number of People Aware of a Secret"
    │   └── "983. Minimum Cost For Tickets"
    │
    ├── House robber disguises — skip/take on a line or circle
    │   │
    │   ├── "746. Min Cost Climbing Stairs"
    │   ├── "213. House Robber II"
    │   ├── "337. House Robber III"
    │   └── "740. Delete and Earn"
    │
    ├── Kadane with extra state
    │   │
    │   ├── "152. Maximum Product Subarray"
    │   └── "918. Maximum Sum Circular Subarray"
    │
    ├── String segmentation (DP / memoized DFS)
    │   │
    │   ├── "139. Word Break"
    │   └── "140. Word Break II"
    │
    ├── LIS pattern (with patience sorting)
    │   │
    │   ├── "300. Longest Increasing Subsequence"
    │   ├── "673. Number of Longest Increasing Subsequence"
    │   ├── "368. Largest Divisible Subset"
    │   ├── "1048. Longest String Chain"
    │   └── "354. Russian Doll Envelopes"
    │
    ├── 0/1 knapsack — subset selection
    │   │
    │   ├── "416. Partition Equal Subset Sum"
    │   ├── "494. Target Sum"
    │   ├── "474. Ones and Zeroes"
    │   └── "1049. Last Stone Weight II"
    │
    ├── Unbounded knapsack — coins & combinations
    │   │
    │   ├── "518. Coin Change II"
    │   ├── "377. Combination Sum IV"
    │   ├── "279. Perfect Squares"
    │   └── "322. Coin Change"
    │
    ├── 2D DP over two strings
    │   │
    │   ├── "72. Edit Distance"
    │   ├── "1143. Longest Common Subsequence"
    │   ├── "115. Distinct Subsequences"
    │   ├── "1312. Minimum Insertion Steps to Make a String Palindrome"
    │   ├── "1639. Number of Ways to Form a Target String Given a Dictionary"
    │   └── "1092. Shortest Common Supersequence"
    │
    ├── Two-sequence & palindrome string DP
    │   │
    │   ├── "97. Interleaving String"
    │   ├── "516. Longest Palindromic Subsequence"
    │   ├── "583. Delete Operation for Two Strings"
    │   ├── "132. Palindrome Partitioning II"
    │   └── "2484. Count Palindromic Subsequences"
    │
    ├── DP — pattern matching (regex / wildcard)
    │   │
    │   ├── "10. Regular Expression Matching"
    │   └── "44. Wildcard Matching"
    │
    ├── Palindromic substrings — expand around center
    │   │
    │   ├── "5. Longest Palindromic Substring"
    │   └── "647. Palindromic Substrings"
    │
    ├── Interval DP — split-point recurrence
    │   │
    │   ├── "96. Unique Binary Search Trees"
    │   ├── "1039. Minimum Score Triangulation of Polygon"
    │   ├── "312. Burst Balloons"
    │   └── "1547. Minimum Cost to Cut a Stick"
    │
    ├── Grid DP — path counts & minimum path sums
    │   │
    │   ├── "118. Pascal's Triangle"
    │   ├── "62. Unique Paths"
    │   ├── "63. Unique Paths II"
    │   ├── "64. Minimum Path Sum"
    │   ├── "120. Triangle"
    │   └── "931. Minimum Falling Path Sum"
    │
    ├── Grid DP — squares, reverse DP & memoized DFS
    │   │
    │   ├── "221. Maximal Square"
    │   ├── "329. Longest Increasing Path in a Matrix"
    │   ├── "741. Cherry Pickup"
    │   └── "174. Dungeon Game"
    │
    ├── Weighted interval scheduling DP
    │   │
    │   ├── "2008. Maximum Earnings From Taxi"
    │   └── "1235. Maximum Profit in Job Scheduling"
    │
    ├── DP over position + small extra state
    │   │
    │   ├── "1824. Minimum Sideway Jumps"
    │   ├── "808. Soup Servings"
    │   ├── "403. Frog Jump"
    │   ├── "514. Freedom Trail"
    │   └── "689. Maximum Sum of 3 Non-Overlapping Subarrays"
    │
    ├── Stock trading as a state machine
    │   │
    │   ├── "121. Best Time to Buy and Sell Stock"
    │   ├── "122. Best Time to Buy and Sell Stock II"
    │   ├── "309. Best Time to Buy and Sell Stock with Cooldown"
    │   ├── "714. Best Time to Buy and Sell Stock with Transaction Fee"
    │   ├── "123. Best Time to Buy and Sell Stock III"
    │   └── "188. Best Time to Buy and Sell Stock IV"
    │
    └── Bitmask DP over subsets
        │
        ├── "1125. Smallest Sufficient Team"
        ├── "847. Shortest Path Visiting All Nodes"
        ├── "1994. The Number of Good Subsets"
        └── "691. Stickers to Spell Word"
```

> **Related Patterns**:
> - Backtracking (memoizing repeated search states avoids exploring the same remaining choices again)
> - Binary Search (finds LIS insertion positions and compatible intervals for scheduling transitions)
> - Bit Manipulation (masks encode chosen items or visited sets in subset DP)
> - Trees & BST (post-order traversal supplies child states before parent transitions)
