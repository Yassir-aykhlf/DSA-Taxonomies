# Intervals & Sweep Pattern Taxonomy

> Sort interval boundaries or events, then sweep in order while tracking active ranges to merge overlaps, schedule resources, and answer coverage queries.

```text
└── Intervals & Sweep
    │
    ├── Intervals — sort then sweep (merge / select / erase)
    │   │
    │   ├── "252. Meeting Rooms"
    │   ├── "56. Merge Intervals"
    │   ├── "435. Non-overlapping Intervals"
    │   ├── "57. Insert Interval"
    │   ├── "986. Interval List Intersections"
    │   ├── "452. Minimum Number of Arrows to Burst Balloons"
    │   ├── "1288. Remove Covered Intervals"
    │   ├── "3169. Count Days Without Meetings"
    │   └── "759. Employee Free Time"
    │
    ├── Event scheduling — sweep with a heap
    │   │
    │   ├── "1353. Maximum Number of Events That Can Be Attended"
    │   ├── "253. Meeting Rooms II"
    │   ├── "1942. The Number of the Smallest Unoccupied Chair"
    │   ├── "436. Find Right Interval"
    │   ├── "2402. Meeting Rooms III"
    │   └── "2251. Number of Flowers in Full Bloom"
    │
    └── Sweep line over events (skyline)
        │
        ├── "1094. Car Pooling"
        ├── "218. The Skyline Problem"
        └── "1851. Minimum Interval to Include Each Query"
```

> **Related Patterns**:
> - Sorting (orders interval endpoints and queries so the sweep advances in one direction)
> - Heap / Priority Queue (tracks the next ending event or best active candidate)
> - Greedy (choosing the earliest ending interval maximizes a compatible selection)
> - Prefix Sums (difference arrays turn boundary events into running overlap counts)
