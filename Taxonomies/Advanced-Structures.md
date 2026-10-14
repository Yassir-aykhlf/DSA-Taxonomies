# Advanced Structures Pattern Taxonomy

> Use merge-sort counting, Fenwick trees, and segment trees for inversion counts, mutable range queries, and interval updates, with coordinate compression or lazy propagation where needed.

```text
└── Advanced Structures
    │
    ├── Merge sort — count inversions
    │   │
    │   ├── "315. Count of Smaller Numbers After Self"
    │   └── "493. Reverse Pairs"
    │
    ├── Fenwick tree (BIT) — point update, range query
    │   │
    │   ├── "307. Range Sum Query - Mutable"
    │   └── "308. Range Sum Query 2D - Mutable"
    │
    └── Segment tree — lazy updates & coordinate compression
        │
        ├── "699. Falling Squares"
        ├── "732. My Calendar III"
        └── "850. Rectangle Area II"
```

> **Related Patterns**:
> - Prefix Sums (Fenwick trees maintain cumulative aggregates as values change)
> - Sorting (merge passes count cross-half pairs; compression ranks distinct coordinates)
> - Bit Manipulation (the lowest set bit determines each Fenwick traversal step)
> - Intervals & Sweep (segment trees track coverage and overlap while events advance)
