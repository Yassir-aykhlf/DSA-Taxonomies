# Linked List Pattern Taxonomy

> Traverse nodes through links and rewire pointers to reverse, remove, split, or rearrange a list — fast/slow pointers locate midpoints and expose cycles.

```text
└── Linked List
    │
    ├── Linked list — reversal (whole / sublist / k-group)
    │   │
    │   ├── "206. Reverse Linked List"
    │   ├── "92. Reverse Linked List II"
    │   ├── "2074. Reverse Nodes in Even Length Groups"
    │   └── "25. Reverse Nodes in k-Group"
    │
    ├── Linked list — fast & slow pointers
    │   │
    │   ├── "141. Linked List Cycle"
    │   ├── "234. Palindrome Linked List"
    │   ├── "876. Middle of the Linked List"
    │   ├── "142. Linked List Cycle II"
    │   ├── "143. Reorder List"
    │   └── "2130. Maximum Twin Sum of a Linked List"
    │
    ├── Floyd's cycle detection — beyond linked lists
    │   │
    │   ├── "202. Happy Number"
    │   ├── "287. Find the Duplicate Number"
    │   └── "457. Circular Array Loop"
    │
    ├── Linked list — add numbers
    │   │
    │   ├── "2. Add Two Numbers"
    │   └── "445. Add Two Numbers II"
    │
    ├── Linked list — remove / dedup nodes
    │   │
    │   ├── "83. Remove Duplicates from Sorted List"
    │   ├── "203. Remove Linked List Elements"
    │   ├── "1474. Delete N Nodes After M Nodes of a Linked List"
    │   ├── "82. Remove Duplicates from Sorted List II"
    │   └── "19. Remove Nth Node From End of List"
    │
    ├── Linked list — structural rearrange
    │   │
    │   ├── "61. Rotate List"
    │   ├── "24. Swap Nodes in Pairs"
    │   ├── "1721. Swapping Nodes in a Linked List"
    │   ├── "1669. Merge In Between Linked Lists"
    │   └── "708. Insert into a Sorted Circular Linked List"
    │
    └── Linked list — split, partition & intersect
        │
        ├── "160. Intersection of Two Linked Lists"
        ├── "328. Odd Even Linked List"
        ├── "86. Partition List"
        ├── "2674. Split a Circular Linked List"
        └── "725. Split Linked List in Parts"
```

> **Related Patterns**:
> - Arrays & Two Pointers (fast/slow and fixed-gap runners locate cycles, midpoints, and positions from the end)
> - Stack & Queue (stacks expose digits from the tail for forward-order addition)
> - Hashing & Grouping (visited-node sets offer alternative cycle and intersection checks)
> - Sorting (merge sort orders linked nodes by splitting and relinking runs)
