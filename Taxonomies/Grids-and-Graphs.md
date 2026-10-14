# Grids & Graphs Pattern Taxonomy

> Traverse cells, nodes, or implicit states in an order suited to the question — tracking connectivity, shortest paths, dependencies, and structural properties across grids and graphs.

```text
└── Grids & Graphs
    │
    ├── Matrix basics — transpose, reshape & diagonals
    │   │
    │   ├── "867. Transpose Matrix"
    │   ├── "2022. Convert 1D Array Into 2D Array"
    │   ├── "766. Toeplitz Matrix"
    │   ├── "832. Flipping an Image"
    │   ├── "1380. Lucky Numbers in a Matrix"
    │   └── "59. Spiral Matrix II"
    │
    ├── Flood fill & connected components
    │   │
    │   ├── "733. Flood Fill"
    │   ├── "200. Number of Islands"
    │   ├── "130. Surrounded Regions"
    │   ├── "695. Max Area of Island"
    │   ├── "547. Number of Provinces"
    │   ├── "417. Pacific Atlantic Water Flow"
    │   ├── "694. Number of Distinct Islands"
    │   └── "827. Making A Large Island"
    │
    ├── Matrix traversal & in-place manipulation
    │   │
    │   ├── "54. Spiral Matrix"
    │   ├── "498. Diagonal Traverse"
    │   ├── "48. Rotate Image"
    │   ├── "73. Set Matrix Zeroes"
    │   ├── "289. Game of Life"
    │   └── "1861. Rotating the Box"
    │
    ├── Matrix simulation & counting
    │   │
    │   ├── "463. Island Perimeter"
    │   ├── "1706. Where Will the Ball Fall"
    │   ├── "2061. Number of Spaces Cleaning Robot Cleaned"
    │   ├── "3071. Minimum Operations to Write the Letter Y on a Grid"
    │   └── "2371. Minimize Maximum Value in a Grid"
    │
    ├── BFS — shortest path in a grid or maze
    │   │
    │   ├── "1926. Nearest Exit from Entrance in Maze"
    │   ├── "909. Snakes and Ladders"
    │   ├── "490. The Maze"
    │   ├── "1197. Minimum Knight Moves"
    │   └── "1293. Shortest Path in a Grid with Obstacles Elimination"
    │
    ├── Multi-source BFS over a grid
    │   │
    │   ├── "542. 01 Matrix"
    │   ├── "1091. Shortest Path in Binary Matrix"
    │   ├── "286. Walls and Gates"
    │   ├── "1162. As Far from Land as Possible"
    │   ├── "934. Shortest Bridge"
    │   ├── "994. Rotting Oranges"
    │   ├── "317. Shortest Distance from All Buildings"
    │   └── "2814. Minimum Time Takes to Reach Destination Without Drowning"
    │
    ├── BFS — shortest path over implicit states
    │   │
    │   ├── "752. Open the Lock"
    │   ├── "127. Word Ladder"
    │   ├── "815. Bus Routes"
    │   ├── "2608. Shortest Cycle in a Graph"
    │   └── "126. Word Ladder II"
    │
    ├── Graph basics — degrees, celebrities & tiny cycles
    │   │
    │   ├── "997. Find the Town Judge"
    │   ├── "1791. Find Center of Star Graph"
    │   ├── "277. Find the Celebrity"
    │   └── "2077. Paths in Maze That Lead to Same Room"
    │
    ├── Graph traversal — reachability
    │   │
    │   ├── "1971. Find if Path Exists in Graph"
    │   ├── "841. Keys and Rooms"
    │   ├── "797. All Paths From Source to Target"
    │   ├── "1376. Time Needed to Inform All Employees"
    │   ├── "1466. Reorder Routes to Make All Paths Lead to the City Zero"
    │   ├── "2101. Detonate the Maximum Bombs"
    │   └── "1377. Frog Position After T Seconds"
    │
    ├── Topological sort (Kahn / DFS)
    │   │
    │   ├── "207. Course Schedule"
    │   ├── "210. Course Schedule II"
    │   ├── "2115. Find All Possible Recipes from Given Supplies"
    │   ├── "851. Loud and Rich"
    │   └── "269. Alien Dictionary"
    │
    ├── Topological order — layered scheduling & longest path in a DAG
    │   │
    │   ├── "1136. Parallel Courses"
    │   ├── "2050. Parallel Courses III"
    │   ├── "2392. Build a Matrix With Conditions"
    │   └── "1203. Sort Items by Groups Respecting Dependencies"
    │
    ├── Graph two-coloring — bipartite check
    │   │
    │   ├── "785. Is Graph Bipartite?"
    │   └── "886. Possible Bipartition"
    │
    ├── Union-Find (DSU) — components & cycle edge
    │   │
    │   ├── "684. Redundant Connection"
    │   ├── "323. Number of Connected Components in an Undirected Graph"
    │   ├── "261. Graph Valid Tree"
    │   ├── "947. Most Stones Removed with Same Row or Column"
    │   └── "959. Regions Cut By Slashes"
    │
    ├── Union-Find — merging, weights & reverse timelines
    │   │
    │   ├── "721. Accounts Merge"
    │   ├── "399. Evaluate Division"
    │   ├── "1319. Number of Operations to Make Network Connected"
    │   ├── "1970. Last Day Where You Can Still Cross"
    │   ├── "924. Minimize Malware Spread"
    │   ├── "839. Similar String Groups"
    │   └── "305. Number of Islands II"
    │
    ├── Dijkstra & Bellman-Ford shortest paths
    │   │
    │   ├── "743. Network Delay Time"
    │   ├── "787. Cheapest Flights Within K Stops"
    │   ├── "1514. Path with Maximum Probability"
    │   └── "1368. Minimum Cost to Make at Least One Valid Path in a Grid"
    │
    ├── Min-heap search over a weighted grid
    │   │
    │   ├── "1631. Path With Minimum Effort"
    │   ├── "778. Swim in Rising Water"
    │   └── "407. Trapping Rain Water II"
    │
    ├── Graph structure — bridges, safe states, Euler tour & MST
    │   │
    │   ├── "1584. Min Cost to Connect All Points"
    │   ├── "802. Find Eventual Safe States"
    │   ├── "332. Reconstruct Itinerary"
    │   ├── "1192. Critical Connections in a Network"
    │   ├── "2360. Longest Cycle in a Graph"
    │   └── "1168. Optimize Water Distribution in a Village"
    │
    └── Clone a structure via hashmap mapping
        │
        ├── "138. Copy List with Random Pointer"
        └── "133. Clone Graph"
```

> **Related Patterns**:
> - Stack & Queue (queues drive BFS frontiers; stacks support iterative DFS)
> - Heap / Priority Queue (prioritizes frontier states for Dijkstra and Prim)
> - Dynamic Programming (topological order lets DAG states reuse completed predecessor results)
> - Hashing & Grouping (maps record visited states and pair original nodes with their clones)
