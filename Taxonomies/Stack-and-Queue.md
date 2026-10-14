# Stack & Queue Pattern Taxonomy

> Use LIFO/FIFO ordering to match brackets, evaluate expressions, and process sequences — monotonic stacks and deques retain candidates for next-element, span, and window queries.

```text
└── Stack & Queue
    │
    ├── Stack — bracket matching / validity
    │   │
    │   ├── "20. Valid Parentheses"
    │   ├── "1249. Minimum Remove to Make Valid Parentheses"
    │   ├── "1963. Minimum Number of Swaps to Make the String Balanced"
    │   └── "32. Longest Valid Parentheses"
    │
    ├── Stack — expression evaluation
    │   │
    │   ├── "227. Basic Calculator II"
    │   ├── "150. Evaluate Reverse Polish Notation"
    │   ├── "224. Basic Calculator"
    │   └── "1106. Parsing A Boolean Expression"
    │
    ├── Stack — scan & process a sequence
    │   │
    │   ├── "1047. Remove All Adjacent Duplicates In String"
    │   ├── "2696. Minimum String Length After Removing Substrings"
    │   ├── "394. Decode String"
    │   ├── "735. Asteroid Collision"
    │   ├── "1209. Remove All Adjacent Duplicates in String II"
    │   ├── "71. Simplify Path"
    │   └── "636. Exclusive Time of Functions"
    │
    ├── Stack design — min/max stacks & queue via stacks
    │   │
    │   ├── "232. Implement Queue using Stacks"
    │   ├── "155. Min Stack"
    │   ├── "2296. Design a Text Editor"
    │   └── "716. Max Stack"
    │
    ├── Monotonic stack — next greater/smaller
    │   │
    │   ├── "496. Next Greater Element I"
    │   ├── "739. Daily Temperatures"
    │   ├── "853. Car Fleet"
    │   ├── "456. 132 Pattern"
    │   ├── "1944. Number of Visible People in a Queue"
    │   ├── "1063. Number of Valid Subarrays"
    │   └── "2454. Next Greater Element IV"
    │
    ├── Monotonic stack — histogram, spans & contribution
    │   │
    │   ├── "907. Sum of Subarray Minimums"
    │   ├── "962. Maximum Width Ramp"
    │   ├── "42. Trapping Rain Water"
    │   ├── "84. Largest Rectangle in Histogram"
    │   └── "85. Maximal Rectangle"
    │
    ├── Monotonic stack — lexicographically optimal subsequence
    │   │
    │   ├── "402. Remove K Digits"
    │   ├── "316. Remove Duplicate Letters"
    │   └── "321. Create Maximum Number"
    │
    └── Monotonic deque — sliding window extremum
        │
        ├── "1438. Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit"
        ├── "239. Sliding Window Maximum"
        └── "683. K Empty Slots"
```

> **Related Patterns**:
> - Strings (stack matching and decoding resolve nested string structure)
> - Sliding Window (monotonic deques track the minimum or maximum inside a moving span)
> - Greedy (discarding dominated elements helps build lexicographically optimal subsequences)
> - Design (combine stacks or add auxiliary state to support queue, minimum, and maximum operations)
