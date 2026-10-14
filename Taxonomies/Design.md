# Design Pattern Taxonomy

> Build stateful APIs by combining maps, arrays, lists, and ordered structures, maintaining the invariants needed for efficient lookup, updates, iteration, and sampling.

```text
└── Design
    │
    ├── Design — eviction caches & frequency buckets
    │   │
    │   ├── "146. LRU Cache"
    │   ├── "460. LFU Cache"
    │   └── "895. Maximum Frequency Stack"
    │
    ├── Design — O(1) hashmap/array-backed structures
    │   │
    │   ├── "706. Design HashMap"
    │   ├── "705. Design HashSet"
    │   ├── "346. Moving Average from Data Stream"
    │   ├── "170. Two Sum III - Data structure design"
    │   ├── "380. Insert Delete GetRandom O(1)"
    │   ├── "622. Design Circular Queue"
    │   ├── "1570. Dot Product of Two Sparse Vectors"
    │   ├── "348. Design Tic-Tac-Toe"
    │   └── "244. Shortest Word Distance II"
    │
    ├── Design — composite O(1) structures (dupes, All-O-1)
    │   │
    │   ├── "1396. Design Underground System"
    │   ├── "381. Insert Delete GetRandom O(1) - Duplicates allowed"
    │   └── "432. All O`one Data Structure"
    │
    ├── Design — time / expiry & rate limiting
    │   │
    │   ├── "359. Logger Rate Limiter"
    │   ├── "933. Number of Recent Calls"
    │   ├── "981. Time Based Key-Value Store"
    │   ├── "1797. Design Authentication Manager"
    │   ├── "362. Design Hit Counter"
    │   └── "1146. Snapshot Array"
    │
    ├── Design — filesystem / path-keyed structures
    │   │
    │   ├── "1166. Design File System"
    │   └── "588. Design In-Memory File System"
    │
    ├── Ordered interval structures — calendars & disjoint streams
    │   │
    │   ├── "731. My Calendar II"
    │   ├── "729. My Calendar I"
    │   ├── "352. Data Stream as Disjoint Intervals"
    │   └── "715. Range Module"
    │
    ├── Encoding / (de)serialization to a string
    │   │
    │   ├── "271. Encode and Decode Strings"
    │   └── "535. Encode and Decode TinyURL"
    │
    ├── Design — controlled iterators
    │   │
    │   ├── "284. Peeking Iterator"
    │   ├── "341. Flatten Nested List Iterator"
    │   └── "1286. Iterator for Combination"
    │
    └── Randomized design — reservoir sampling & shuffle
        │
        ├── "382. Linked List Random Node"
        ├── "398. Random Pick Index"
        └── "384. Shuffle an Array"
```

> **Related Patterns**:
> - Hashing & Grouping (maps and frequency buckets provide the core lookup state)
> - Linked List (doubly linked lists support eviction order and constant-time relinking)
> - Trie (shared path prefixes organize filesystems and hierarchical keys)
> - Intervals & Sweep (ordered boundaries support calendars and disjoint-range operations)
