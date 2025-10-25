# 🚀 DSA Algorithm Patterns for MAANG Interview Prep

Welcome to my **Algorithm Patterns Repository** — a curated collection of the most essential algorithmic patterns every Software Engineer should master before MAANG-level interviews.  
All implementations are written in **Python**, focusing on clarity, efficiency, and reusability.

---

## 📚 Overview

This repository covers **20 core algorithm patterns** that repeatedly appear in top company interviews (Google, Amazon, Meta, Apple, Netflix, etc.).  
Instead of memorizing random problems, these patterns help you **identify problem types instantly** and design optimal solutions under pressure.

---

## 🧩 Algorithm Patterns

### 1️⃣ Sliding Window
**Used for:** Subarrays, substrings, fixed or variable-length windows  
**Implementations:**
- `max_sum_subarray(nums, k)`
- `longest_substring_without_repeat(s)`

---

### 2️⃣ Two Pointers
**Used for:** Sorted arrays, linked lists, searching pairs  
**Implementations:**
- `two_sum_sorted(nums, target)`
- `remove_duplicates(nums)`

---

### 3️⃣ Fast & Slow Pointers (Cycle Detection)
**Used for:** Detecting loops or midpoints in linked lists  
**Implementations:**
- `has_cycle(head)`
- `find_middle(head)`

---

### 4️⃣ Merge Intervals
**Used for:** Merging overlapping intervals or time windows  
**Implementations:**
- `merge_intervals(intervals)`
- `insert_interval(intervals, new_interval)`

---

### 5️⃣ Binary Search
**Used for:** Sorted data, monotonic conditions, decision problems  
**Implementations:**
- `binary_search(nums, target)`
- `search_rotated(nums, target)`
- `min_in_rotated(nums)`

---

### 6️⃣ Divide and Conquer
**Used for:** Recursive subproblems, sorting, and tree algorithms  
**Implementations:**
- `merge_sort(nums)`
- `quick_sort(nums)`

---

### 7️⃣ Recursion & Backtracking
**Used for:** Generating all possibilities, permutations, and combinations  
**Implementations:**
- `generate_subsets(nums)`
- `generate_permutations(nums)`
- `solve_n_queens(n)`

---

### 8️⃣ Dynamic Programming (DP)
**Used for:** Problems with overlapping subproblems and optimal substructure  
**Implementations:**
- `fibonacci(n)` – memoization + tabulation  
- `coin_change(coins, amount)`  
- `knapsack(weights, values, W)`  
- `longest_common_subsequence(s1, s2)`  
- `edit_distance(s1, s2)`

---

### 9️⃣ Top-Down vs Bottom-Up DP
**Goal:** Understand memoization vs tabulation by implementing both styles.

---

### 🔟 Greedy Algorithms
**Used for:** Local choices leading to global optimum  
**Implementations:**
- `activity_selection(intervals)`
- `fractional_knapsack(weights, values, W)`
- `minimum_coins(coins, amount)`

---

### 1️⃣1️⃣ Graph Traversal
**Used for:** Networks, dependencies, and connectivity problems  
**Implementations:**
- `bfs(graph, start)`
- `dfs(graph, start)`
- `topological_sort(graph)`
- `detect_cycle_directed(graph)`

---

### 1️⃣2️⃣ Shortest Path Algorithms
**Used for:** Minimum distance or cost path problems  
**Implementations:**
- `dijkstra(graph, start)`
- `bellman_ford(graph, start)`
- `floyd_warshall(graph)`

---

### 1️⃣3️⃣ Union-Find / Disjoint Set
**Used for:** Connected components, Kruskal’s MST, friend groups  
**Implementations:**
- `UnionFind` class with `find()` and `union()` (path compression + union by rank)

---

### 1️⃣4️⃣ Minimum Spanning Tree
**Used for:** Connecting all vertices with minimal total weight  
**Implementations:**
- `kruskal(graph)`
- `prim(graph)`

---

### 1️⃣5️⃣ Heap / Priority Queue
**Used for:** Top-K problems, scheduling, greedy optimizations  
**Implementations:**
- `k_largest(nums, k)`
- `merge_k_sorted_lists(lists)`
- `reorganize_string(s)`

---

### 1️⃣6️⃣ Binary Search on Answer
**Used for:** Problems where the answer space is monotonic  
**Implementations:**
- `min_capacity_to_ship(weights, days)`
- `koko_eating_speed(piles, h)`

---

### 1️⃣7️⃣ Bit Manipulation
**Used for:** XOR tricks, subsets, and state compression  
**Implementations:**
- `find_single_number(nums)`
- `count_bits(n)`
- `subset_generation_using_bits(nums)`

---

### 1️⃣8️⃣ Matrix / Grid Traversal
**Used for:** Flood fill, pathfinding, and island counting problems  
**Implementations:**
- `num_islands(grid)`
- `flood_fill(image, sr, sc, newColor)`
- `shortest_path_in_binary_matrix(grid)`

---

### 1️⃣9️⃣ Top-K / Heap-Based Problems
**Used for:** Ranking, frequency, and median problems  
**Implementations:**
- `kth_largest(nums, k)`
- `frequency_sort(nums)`
- `top_k_frequent(nums, k)`

---

### 2️⃣0️⃣ Design & Miscellaneous Patterns
**Used for:** System design-style coding questions  
**Implementations:**
- `LRUCache`  
- `MinStack`  
- `Trie`

---

Each pattern folder contains:
- **Python Implementations**
- **README.md** explaining the concept, use-cases, and time complexity.

---

## 💪 Why This Matters

These 20 algorithmic patterns cover **90%+ of MAANG interview questions**.  
Once you master them, you’ll be able to identify any problem’s core pattern instantly and design optimal solutions with confidence.

---

### 👨‍💻 Author
**Akash Jagannath Kolte**  
MS in Computer Science – SUNY Buffalo  
Full stack developer and AI Engineer building intelligent systems

---
⭐️ *If you find this useful, consider giving the repo a star — it helps others learn too!*
