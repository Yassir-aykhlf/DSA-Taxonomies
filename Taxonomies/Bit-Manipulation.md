# Bit Manipulation Pattern Taxonomy

> Work directly with binary digits using XOR, masks, shifts, and bit counts to isolate values, transform representations, and reason about aggregate AND/OR states.

```text
└── Bit Manipulation
    │
    ├── XOR identities — find the unique
    │   │
    │   ├── "136. Single Number"
    │   ├── "461. Hamming Distance"
    │   ├── "389. Find the Difference"
    │   ├── "137. Single Number II"
    │   └── "260. Single Number III"
    │
    ├── Bits — count, reverse & test
    │   │
    │   ├── "191. Number of 1 Bits"
    │   ├── "190. Reverse Bits"
    │   ├── "338. Counting Bits"
    │   ├── "231. Power of Two"
    │   └── "1009. Complement of Base 10 Integer"
    │
    ├── Bit tricks — add without +, range AND & Gray code
    │   │
    │   ├── "1863. Sum of All Subset XOR Totals"
    │   ├── "371. Sum of Two Integers"
    │   ├── "201. Bitwise AND of Numbers Range"
    │   ├── "2802. Find The K-th Lucky Number"
    │   └── "1611. Minimum One Bit Operations to Make Integers Zero"
    │
    └── Bitwise — AND/OR over subarrays & popcount bounds
        │
        ├── "898. Bitwise ORs of Subarrays"
        ├── "2419. Longest Subarray With Maximum Bitwise AND"
        ├── "2749. Minimum Operations to Make the Integer Zero"
        └── "982. Triples with Bitwise AND Equal To Zero"
```

> **Related Patterns**:
> - Math & Geometry (binary decomposition connects arithmetic identities with counting arguments)
> - Dynamic Programming (bitmasks encode subsets; bit counts and reachable states admit recurrences)
> - Prefix Sums (prefix XOR answers a range by combining two prefix states)
> - Trie (a binary trie chooses bit paths to maximize XOR)
