# Strings Pattern Taxonomy

> Scan and transform character sequences to parse values, simulate arithmetic, construct output, and match patterns — reusing prefix information or rolling hashes to avoid repeated comparisons.

```text
└── Strings
    │
    ├── String — number / roman / words conversion
    │   │
    │   ├── "13. Roman to Integer"
    │   ├── "12. Integer to Roman"
    │   └── "273. Integer to English Words"
    │
    ├── String — big-integer arithmetic
    │   │
    │   ├── "415. Add Strings"
    │   ├── "66. Plus One"
    │   ├── "67. Add Binary"
    │   ├── "989. Add to Array-Form of Integer"
    │   ├── "43. Multiply Strings"
    │   └── "1073. Adding Two Negabinary Numbers"
    │
    ├── String — parse, validate & format
    │   │
    │   ├── "165. Compare Version Numbers"
    │   ├── "38. Count and Say"
    │   ├── "468. Validate IP Address"
    │   ├── "8. String to Integer (atoi)"
    │   ├── "972. Equal Rational Numbers"
    │   └── "420. Strong Password Checker"
    │
    ├── String — single-pass scan & assembly
    │   │
    │   ├── "14. Longest Common Prefix"
    │   ├── "293. Flip Game"
    │   ├── "6. Zigzag Conversion"
    │   ├── "68. Text Justification"
    │   ├── "761. Special Binary String"
    │   └── "3406. Find the Lexicographically Largest String From the Box II"
    │
    ├── Next permutation algorithm
    │   │
    │   ├── "31. Next Permutation"
    │   ├── "556. Next Greater Element III"
    │   └── "1842. Next Palindrome Using Same Digits"
    │
    ├── KMP & prefix-function string matching
    │   │
    │   ├── "28. Find the Index of the First Occurrence in a String"
    │   ├── "459. Repeated Substring Pattern"
    │   ├── "796. Rotate String"
    │   └── "1392. Longest Happy Prefix"
    │
    └── Rolling hash on substrings
        │
        ├── "187. Repeated DNA Sequences"
        └── "1044. Longest Duplicate Substring"
```

> **Related Patterns**:
> - Arrays & Two Pointers (pointer scans support digit arithmetic and next-permutation rearrangement)
> - Hashing & Grouping (substring hashes provide compact keys for repetition checks)
> - Trie (shared prefix paths support dictionary lookup and prefix matching)
> - Math & Geometry (place value and number bases guide numeric string conversions and arithmetic)
