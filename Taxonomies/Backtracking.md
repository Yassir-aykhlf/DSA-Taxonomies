# Backtracking Pattern Taxonomy

> Build a candidate one choice at a time, recurse, then undo — prune invalid branches and skip equivalent choices while enumerating combinations, assignments, and paths.

```text
└── Backtracking
    │
    ├── Backtracking — subsets / combinations
    │   │
    │   ├── "17. Letter Combinations of a Phone Number"
    │   ├── "40. Combination Sum II"
    │   ├── "39. Combination Sum"
    │   ├── "78. Subsets"
    │   ├── "1079. Letter Tile Possibilities"
    │   └── "784. Letter Case Permutation"
    │
    ├── Backtracking — dedup variants (subsets II / combos / non-decreasing)
    │   │
    │   ├── "90. Subsets II"
    │   ├── "77. Combinations"
    │   ├── "216. Combination Sum III"
    │   └── "491. Non-decreasing Subsequences"
    │
    ├── Backtracking — permutations
    │   │
    │   ├── "46. Permutations"
    │   └── "47. Permutations II"
    │
    ├── Backtracking — enumerate valid configurations
    │   │
    │   ├── "401. Binary Watch"
    │   ├── "22. Generate Parentheses"
    │   ├── "93. Restore IP Addresses"
    │   └── "301. Remove Invalid Parentheses"
    │
    ├── Backtracking — partition into valid pieces
    │   │
    │   ├── "131. Palindrome Partitioning"
    │   ├── "1593. Split a String Into the Max Number of Unique Substrings"
    │   ├── "842. Split Array into Fibonacci Sequence"
    │   └── "306. Additive Number"
    │
    ├── Backtracking — constraint placement (queens & sudoku)
    │   │
    │   ├── "36. Valid Sudoku"
    │   ├── "51. N-Queens"
    │   ├── "37. Sudoku Solver"
    │   └── "52. N-Queens II"
    │
    ├── Backtracking — assign items into k buckets
    │   │
    │   ├── "698. Partition to K Equal Sum Subsets"
    │   ├── "473. Matchsticks to Square"
    │   ├── "2850. Minimum Moves to Spread Stones Over Grid"
    │   └── "465. Optimal Account Balancing"
    │
    ├── Backtracking — build and evaluate expressions
    │   │
    │   ├── "241. Different Ways to Add Parentheses"
    │   ├── "282. Expression Add Operators"
    │   └── "679. 24 Game"
    │
    └── Backtracking — grid path search
        │
        ├── "79. Word Search"
        └── "980. Unique Paths III"
```

> **Related Patterns**:
> - Dynamic Programming (memoization reuses repeated search states when their remaining choices match)
> - Grids & Graphs (path search is DFS with visited state restored between branches)
> - Bit Manipulation (masks track used items and occupied columns or diagonals)
> - Sorting (ordered candidates make duplicate skipping and target-sum pruning easier)
