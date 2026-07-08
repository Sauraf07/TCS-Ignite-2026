# Potential Coding Problems for Upcoming Examination

This document outlines a comprehensive list of coding problem categories, ranging from basic to advanced, that may appear in a computer science coding examination. It is organized by difficulty tier, then by concept area, so you can use it as a checklist while structuring your practice.

---

## I. Basic Level Problems

These problems typically assess fundamental programming constructs, syntax fluency, and simple logic-building. They rarely require any data structure beyond a single variable or array.

**Core Language Mechanics**
- **Variable Declaration & Manipulation**: Declaring, initializing, and modifying variables of different data types; type casting/conversion.
- **Arithmetic Operations**: Simple calculations, operator precedence, integer vs. floating-point division, modulo-based problems.
- **Conditional Statements**: `if` / `else if` / `else` and `switch`-case logic for decision-making (e.g., grading systems, simple classifiers).
- **Loops**: `for`, `while`, `do-while` loops for repetitive tasks — summing series, counting occurrences, printing number/star patterns.
- **Basic Input/Output**: Reading from standard input and formatting output correctly (a common source of silly errors in timed tests).
- **Simple Function/Method Definition**: Writing and calling functions/methods for modularity, understanding parameters vs. return values.

**Basic Data Handling**
- **String Manipulation (Basic)**: Concatenation, length, character access/indexing, case conversion, simple equality/lexicographic comparisons.
- **Array/List Traversal**: Iterating through elements, printing in reverse, finding sum/count of specific elements.
- **Basic Math Problems**: Checking even/odd, factorial, digit sum/reversal, Armstrong numbers, prime check (brute-force), simple series generation (Fibonacci by iteration).
- **Pattern Printing**: Number/star/character pyramid and triangle patterns using nested loops — a very common "warm-up" coding question in placement-style tests.

---

## II. Intermediate Level Problems

These problems build on basic constructs, introducing linear data structures, elementary algorithms, and moderately layered logic.

**Strings**
- **Advanced String Manipulation**: Substring extraction, searching within strings, character frequency counts, anagram checks, palindrome checks, string reversal without built-in functions.
- **String Parsing/Tokenizing**: Splitting on delimiters, basic validation (e.g., balanced case checks, simple format validation).

**Arrays & Matrices**
- **Array/List Operations**: Searching (linear, binary), finding min/max/second-max, rotating an array, removing duplicates, merging two sorted arrays.
- **Two-Pointer & Sliding Window (Introductory)**: Pair-sum problems, finding subarrays with a given sum, maximum sum subarray of fixed size.
- **Two-Dimensional Arrays (Matrices)**: Traversal (row-wise/column-wise/diagonal/spiral), matrix addition/multiplication, transpose, searching in row/column-sorted matrices.

**Linear Data Structures**
- **Stacks & Queues**: Implementation from scratch and applied use — balanced parentheses/bracket matching, next-greater-element, simple expression evaluation, queue-based simulations.
- **Linked Lists**: Singly and doubly linked lists — traversal, insertion/deletion at a position, reversing a list, detecting a cycle, finding the middle node.

**Foundational Algorithms**
- **Recursion (Introductory)**: Factorial, Fibonacci, sum of digits, simple recursive traversal — building comfort with the call stack and base cases.
- **Basic Searching Algorithms**: Linear Search and Binary Search, including their preconditions and complexity.
- **Basic Sorting Algorithms**: Bubble Sort, Selection Sort, Insertion Sort — implementation plus understanding of their time/space complexity trade-offs.
- **Bitwise Operations**: Using `&`, `|`, `^`, `~`, `<<`, `>>` for tasks like checking power-of-two, counting set bits, swapping without a temp variable.
- **Basic Number Theory**: Prime number checks/sieve basics, GCD/LCM (Euclidean algorithm), perfect square/perfect number checks, simple modular arithmetic.

**Basic Object-Oriented Concepts** *(relevant if the test allows Java/C++/Python and touches OOP)*
- **Class & Object Design**: Defining simple classes with attributes/methods, constructors.
- **Basic OOP Pillars**: Simple problems demonstrating encapsulation, inheritance, or polymorphism (e.g., a small shape/animal hierarchy).

---

## III. Advanced Level Problems

These problems require strong command of non-linear data structures, algorithmic paradigms, and complexity analysis. They're less common in shorter timed tests but worth knowing if the exam allows more time or targets advanced/digital-track roles.

**Trees**
- **Binary Trees**: Traversals (Inorder, Preorder, Postorder, Level Order), computing height/diameter, checking balanced/mirror/symmetric properties.
- **Binary Search Trees (BST)**: Insertion, deletion, searching, validating BST property, finding LCA (lowest common ancestor).
- **Balanced Trees (Conceptual)**: AVL trees, Red-Black trees — high-level understanding of rotations and why balancing matters, rather than full implementation.
- **Heaps**: Min-heap/max-heap implementation, heapify operation, priority-queue-based problems (e.g., k-largest elements, merging k sorted lists).
- **Tries (Prefix Trees)**: Insertion/search, applications like autocomplete or prefix-matching.

**Graphs**
- **Representations**: Adjacency matrix vs. adjacency list trade-offs.
- **Traversals**: Breadth-First Search (BFS) and Depth-First Search (DFS), and their applications (connected components, flood fill).
- **Shortest Path Algorithms**: Dijkstra's Algorithm, Bellman-Ford Algorithm (including handling negative weights).
- **Minimum Spanning Tree (MST)**: Prim's Algorithm, Kruskal's Algorithm (often paired with Union-Find).
- **Union-Find / Disjoint Set**: Cycle detection, connectivity queries, Kruskal's MST support.
- **Topological Sort**: Ordering tasks with dependencies (DAG-based problems).
- **Cycle Detection**: In both directed and undirected graphs.

**Sorting & Divide-and-Conquer**
- **Advanced Sorting Algorithms**: Merge Sort, Quick Sort — implementation, worst/average case analysis, and stability considerations.
- **Divide and Conquer (General Paradigm)**: Problems that split input, solve recursively, and combine results (beyond just sorting) — e.g., finding max/min pair, closest pair of points.

**Dynamic Programming**
- **Identifying DP Structure**: Recognizing overlapping subproblems and optimal substructure.
- **Memoization vs. Tabulation**: Top-down vs. bottom-up implementation trade-offs.
- **Classic DP Problems**: Fibonacci with memoization, 0/1 Knapsack, Unbounded Knapsack, Longest Common Subsequence (LCS), Longest Increasing Subsequence (LIS), Edit Distance, Coin Change, Matrix Chain Multiplication.

**Greedy Algorithms**
- **Locally-Optimal-Choice Problems**: Activity Selection, Fractional Knapsack, Job Sequencing with Deadlines, Huffman Coding (conceptual).

**Backtracking**
- **Exhaustive Search with Pruning**: N-Queens, Sudoku Solver, generating all Permutations/Combinations/Subsets, Rat-in-a-Maze style path problems.

**Hashing**
- **Hash Table Concepts**: Collision resolution (chaining, open addressing), designing a hash-based frequency counter, two-sum-style problems solved via hashing for O(n) lookups.

**Advanced/Specialized Data Structures** *(less common, but possible in harder rounds)*
- **Fenwick Tree (Binary Indexed Tree)**: Conceptual understanding and prefix-sum/range-update applications.
- **Segment Tree**: Range query and range update problems (sum, min/max over a range).

**String Algorithms**
- **Pattern Matching**: KMP Algorithm, Rabin-Karp Algorithm — for efficient substring search beyond brute force.
- **Other String Problems**: Longest Palindromic Substring, string compression, anagram grouping at scale.

**Computational Geometry (Basic)** *(rarely tested in placement-style exams, but occasionally appears)*
- Convex Hull, Line Segment Intersection, basic coordinate geometry problems.

---

## How to Use This List

- Treat the **Basic** tier as non-negotiable fluency — these should be solvable quickly and without hesitation, since timed exams reward speed here.
- The **Intermediate** tier is usually where most placement-style coding questions actually live — prioritize deep practice on arrays, strings, linked lists, stacks/queues, and basic searching/sorting.
- The **Advanced** tier is worth reviewing conceptually (know what each technique is for and when to reach for it) even if you don't have time to master every implementation — recognizing "this is a DP problem" or "this needs BFS" is often the harder skill, more so than writing perfect code.
- This list is intentionally broad and general to CS curricula; it is not a claim about what any specific exam will contain.