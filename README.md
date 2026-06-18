# DSA Pattern Taxonomy

A pattern-organized index of ~600 LeetCode problems. Each file decomposes one pattern into sub-patterns
and maps them to representative problems.

## How to use

The tiers below are an ordered learning path. Inside a file, scan the sub-pattern list to find
the technique a problem needs, then jump to similar problems.

## Patterns

### Tier 1 — Foundations
| Pattern | Core idea |
|---------|-----------|
| [01. Two Pointers](Taxonomies/01.%20Two%20Pointers.md) | Two indices sweep a sequence to replace nested loops (O(n²) → O(n)). |
| [02. Hash Table](Taxonomies/02.%20Hash%20Table.md) | O(1) average lookup/insert; the default answer to "have I seen this?". |
| [03. Stack & Queue](Taxonomies/03.%20Stack%20and%20Queue.md) | LIFO/FIFO ordering; monotonic stacks, parsing, BFS frontiers. |
| [04. Linked List](Taxonomies/04.%20Linked%20List.md) | Pointer relinking, dummy heads, fast/slow traversal. |
| [05. Sorting](Taxonomies/05.%20Sorting.md) | Ordering as preprocessing; comparison vs non-comparison sorts. |

### Tier 2 — Core algorithms
| Pattern | Core idea |
|---------|-----------|
| [06. Traversal Algorithms](Taxonomies/06.%20Traversal%20Algorithms.md) | DFS/BFS over trees and graphs, topological order. |
| [07. Binary Search](Taxonomies/07.%20Binary%20Search.md) | Halve a sorted/monotonic search space — including "search on the answer". |
| [08. Heap / Priority Queue](Taxonomies/08.%20Heap%20Priority%20Queue.md) | Always-ready min/max; top-K, scheduling, k-way merge. |
| [09. Prefix Sum](Taxonomies/09.%20Prefix%20Sum.md) | Precompute cumulative aggregates for O(1) range queries. |

### Tier 3 — Specialized
| Pattern | Core idea |
|---------|-----------|
| [10. Greedy Algorithms](Taxonomies/10.%20Greedy%20Algorithms.md) | Locally optimal choices that are provably globally optimal. |
| [11. Backtracking](Taxonomies/11.%20Backtracking.md) | Systematic search with pruning over combinatorial spaces. |
| [12. Dynamic Programming](Taxonomies/12.%20Dynamic%20Programming.md) | Overlapping subproblems + optimal substructure. |
| [13. Divide & Conquer](Taxonomies/13.%20Divide%20and%20Conquer.md) | Split, solve recursively, combine. |

### Tier 4 — Advanced
| Pattern | Core idea |
|---------|-----------|
| [14. Trie](Taxonomies/14.%20Trie.md) | Prefix tree for string and word lookups. |
| [15. Union Find](Taxonomies/15.%20Union%20Find.md) | Near-O(1) connectivity with path compression + union by rank. |
| [16. Bit Manipulation](Taxonomies/16.%20Bit%20Manipulation.md) | Bitwise tricks, masks, XOR identities, bitmask DP. |
| [17. Segment Tree & Fenwick Tree](Taxonomies/17.%20Segment%20Tree%20and%20Fenwick%20Tree.md) | Log-time range queries/updates on mutable arrays. |
| [18. Combinatorics & Number Theory](Taxonomies/18.%20Combinatorics%20and%20Number%20Theory.md) | Counting, modular arithmetic, primes, gcd. |
| [19. Design Patterns](Taxonomies/19.%20Design%20Pattern.md) | Building custom data structures to hit required complexities. |

---

All 19 patterns live in [`Taxonomies/`](Taxonomies/). Contributions and
corrections welcome.
