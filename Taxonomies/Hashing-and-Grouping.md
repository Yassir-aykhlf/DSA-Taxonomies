# Hashing & Grouping Pattern Taxonomy

> Count occurrences, group items by canonical keys, and track mappings or positions so repeated comparisons become hash lookups.

```text
└── Hashing & Grouping
    │
    ├── Frequency counting — tallies, parity & multiset checks
    │   │
    │   ├── "383. Ransom Note"
    │   ├── "1160. Find Words That Can Be Formed by Characters"
    │   ├── "409. Longest Palindrome"
    │   ├── "266. Palindrome Permutation"
    │   ├── "1207. Unique Number of Occurrences"
    │   ├── "1790. Check if One String Swap Can Make Strings Equal"
    │   ├── "771. Jewels and Stones"
    │   └── "961. N-Repeated Element in Size 2N Array"
    │
    ├── Frequency signature — anagram & canonical-key grouping
    │   │
    │   ├── "242. Valid Anagram"
    │   ├── "49. Group Anagrams"
    │   ├── "1347. Minimum Number of Steps to Make Two Strings Anagram"
    │   ├── "249. Group Shifted Strings"
    │   ├── "1072. Flip Columns For Maximum Number of Equal Rows"
    │   ├── "609. Find Duplicate File in System"
    │   ├── "966. Vowel Spellchecker"
    │   └── "869. Reordered Power of 2"
    │
    ├── Hashing — bijection mapping
    │   │
    │   ├── "205. Isomorphic Strings"
    │   └── "290. Word Pattern"
    │
    ├── Hashmap grouping — runs & first-unique scans
    │   │
    │   ├── "387. First Unique Character in a String"
    │   ├── "696. Count Binary Substrings"
    │   ├── "1086. High Five"
    │   ├── "1180. Count Substrings with Only One Distinct Letter"
    │   ├── "299. Bulls and Cows"
    │   ├── "1181. Before and After Puzzle"
    │   └── "2768. Number of Black Blocks"
    │
    └── Last-seen index — contribution & self-contained substrings
        │
        ├── "2262. Total Appeal of A String"
        └── "3104. Find Longest Self-Contained Substring"
```

> **Related Patterns**:
> - Arrays & Two Pointers (seen-value maps support complement matching during an array scan)
> - Sorting (sorting letters creates a canonical key for anagram grouping)
> - Sliding Window (frequency maps track the counts inside a moving span)
> - Strings (character counts, signatures, and occurrence indices organize string comparisons)
