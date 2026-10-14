# Trie Pattern Taxonomy

> Share prefixes in a tree of characters, digits, or bits, then traverse or augment its nodes for dictionary lookup, lexicographic ordering, and maximum-XOR queries.

```text
└── Trie
    │
    ├── Trie — build & query (insert / search / wildcard)
    │   │
    │   ├── "1065. Index Pairs of a String"
    │   ├── "1455. Check If a Word Occurs As a Prefix of Any Word in a Sentence"
    │   ├── "208. Implement Trie (Prefix Tree)"
    │   ├── "1268. Search Suggestions System"
    │   ├── "211. Design Add and Search Words Data Structure"
    │   ├── "3043. Find the Length of the Longest Common Prefix"
    │   └── "212. Word Search II"
    │
    ├── Trie — dictionary walks & augmented nodes
    │   │
    │   ├── "648. Replace Words"
    │   ├── "677. Map Sum Pairs"
    │   ├── "720. Longest Word in Dictionary"
    │   ├── "1858. Longest Word With All Prefixes"
    │   ├── "745. Prefix and Suffix Search"
    │   ├── "336. Palindrome Pairs"
    │   ├── "3093. Longest Common Suffix Queries"
    │   └── "1032. Stream of Characters"
    │
    └── Implicit & binary tries — lexicographic order & max XOR
        │
        ├── "386. Lexicographical Numbers"
        ├── "421. Maximum XOR of Two Numbers in an Array"
        └── "440. K-th Smallest in Lexicographical Order"
```

> **Related Patterns**:
> - Strings (prefix and suffix matching traverse characters in forward or reverse order)
> - Backtracking (a trie prunes branches in wildcard lookup and grid word search)
> - Bit Manipulation (a binary trie prefers opposite bits to maximize XOR)
> - Design (custom node metadata supports aggregate values and search suggestions)
