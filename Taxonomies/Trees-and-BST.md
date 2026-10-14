# Trees & BST Pattern Taxonomy

> Traverse a tree in the order the question needs, carrying state down, combining subtree results upward, or exploiting BST order to locate values and relationships.

```text
└── Trees & BST
    │
    ├── Tree BFS — level-order traversal
    │   │
    │   ├── "637. Average of Levels in Binary Tree"
    │   ├── "199. Binary Tree Right Side View"
    │   ├── "102. Binary Tree Level Order Traversal"
    │   ├── "103. Binary Tree Zigzag Level Order Traversal"
    │   ├── "116. Populating Next Right Pointers in Each Node"
    │   ├── "662. Maximum Width of Binary Tree"
    │   └── "117. Populating Next Right Pointers in Each Node II"
    │
    ├── Iterative DFS with an explicit stack
    │   │
    │   ├── "144. Binary Tree Preorder Traversal"
    │   ├── "94. Binary Tree Inorder Traversal"
    │   └── "145. Binary Tree Postorder Traversal"
    │
    ├── Tree DFS — return a value up (post-order gain)
    │   │
    │   ├── "543. Diameter of Binary Tree"
    │   ├── "104. Maximum Depth of Binary Tree"
    │   ├── "124. Binary Tree Maximum Path Sum"
    │   ├── "1373. Maximum Sum BST in Binary Tree"
    │   ├── "968. Binary Tree Cameras"
    │   └── "2246. Longest Path With Different Adjacent Characters"
    │
    ├── Root-to-leaf DFS — depth, balance & path sums
    │   │
    │   ├── "111. Minimum Depth of Binary Tree"
    │   ├── "110. Balanced Binary Tree"
    │   ├── "112. Path Sum"
    │   └── "437. Path Sum III"
    │
    ├── DFS — collect paths & carry state down
    │   │
    │   ├── "257. Binary Tree Paths"
    │   ├── "129. Sum Root to Leaf Numbers"
    │   ├── "1448. Count Good Nodes in Binary Tree"
    │   ├── "113. Path Sum II"
    │   └── "364. Nested List Weight Sum II"
    │
    ├── Tree — structural recursion & comparison
    │   │
    │   ├── "226. Invert Binary Tree"
    │   ├── "101. Symmetric Tree"
    │   ├── "572. Subtree of Another Tree"
    │   ├── "100. Same Tree"
    │   ├── "872. Leaf-Similar Trees"
    │   ├── "965. Univalued Binary Tree"
    │   ├── "1367. Linked List in Binary Tree"
    │   └── "1110. Delete Nodes And Return Forest"
    │
    ├── BST — in-order property, validation & iteration
    │   │
    │   ├── "270. Closest Binary Search Tree Value"
    │   ├── "653. Two Sum IV - Input is a BST"
    │   ├── "98. Validate Binary Search Tree"
    │   ├── "230. Kth Smallest Element in a BST"
    │   ├── "235. Lowest Common Ancestor of a Binary Search Tree"
    │   ├── "450. Delete Node in a BST"
    │   ├── "173. Binary Search Tree Iterator"
    │   └── "285. Inorder Successor in BST"
    │
    ├── Tree — LCA & paths between nodes
    │   │
    │   ├── "236. Lowest Common Ancestor of a Binary Tree"
    │   ├── "863. All Nodes Distance K in Binary Tree"
    │   ├── "2096. Step-By-Step Directions From a Binary Tree Node to Another"
    │   ├── "1650. Lowest Common Ancestor of a Binary Tree III"
    │   └── "2277. Closest Node to Path in Tree"
    │
    ├── Build a tree from traversals or sorted input
    │   │
    │   ├── "108. Convert Sorted Array to Binary Search Tree"
    │   ├── "105. Construct Binary Tree from Preorder and Inorder Traversal"
    │   ├── "106. Construct Binary Tree from Inorder and Postorder Traversal"
    │   ├── "109. Convert Sorted List to Binary Search Tree"
    │   └── "1028. Recover a Tree From Preorder Traversal"
    │
    ├── Tree — specialized traversal orders
    │   │
    │   ├── "513. Find Bottom Left Tree Value"
    │   ├── "545. Boundary of Binary Tree"
    │   ├── "314. Binary Tree Vertical Order Traversal"
    │   └── "987. Vertical Order Traversal of a Binary Tree"
    │
    ├── Complete-tree properties
    │   │
    │   ├── "958. Check Completeness of a Binary Tree"
    │   └── "222. Count Complete Tree Nodes"
    │
    ├── Tree (de)serialize & flatten
    │   │
    │   ├── "114. Flatten Binary Tree to Linked List"
    │   ├── "449. Serialize and Deserialize BST"
    │   └── "297. Serialize and Deserialize Binary Tree"
    │
    └── Tree global answers — leaf pruning, re-rooting & diameters
        │
        ├── "310. Minimum Height Trees"
        ├── "1245. Tree Diameter"
        ├── "2603. Collect Coins in a Tree"
        ├── "2858. Minimum Edge Reversals So Every Node Is Reachable"
        ├── "834. Sum of Distances in Tree"
        ├── "2458. Height of Binary Tree After Subtree Removal Queries"
        └── "3203. Find Minimum Diameter After Merging Two Trees"
```

> **Related Patterns**:
> - Stack & Queue (queues drive level-order BFS; explicit stacks support DFS and lazy iteration)
> - Dynamic Programming (subtree states and re-rooting combine local results into global tree answers)
> - Grids & Graphs (tree edges support distance searches and leaf-pruning traversals)
> - Backtracking (path collection records a choice on descent and undoes it on return)
