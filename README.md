# JavaScript Algorithms and Data Structures
### _Read this in [Vietnamese](README.vi.md)_
---
>This repository contains JavaScript based examples of many
popular algorithms and data structures.
>
>Each algorithm and data structure has its own separate README
with related explanations and links for further reading (including ones
to YouTube videos).

## Data Structures

A data structure is a particular way of organizing and storing data in a computer so that it can
be accessed and modified efficiently. More precisely, a data structure is a collection of data
values, the relationships among them, and the functions or operations that can be applied to
the data.

`B` - Beginner, `A` - Advanced

* `B` [Linked List](src/en/data-structures/linked-list)
* `B` [Doubly Linked List](src/en/data-structures/doubly-linked-list)
* `B` [Queue](src/en/data-structures/queue)
* `B` [Stack](src/en/data-structures/stack)
* `B` [Hash Table](src/en/data-structures/hash-table)
* `B` [Heap](src/en/data-structures/heap) - max and min heap versions
* `B` [Priority Queue](src/en/data-structures/priority-queue)
* `A` [Trie](src/en/data-structures/trie)
* `A` [Tree](src/en/data-structures/tree)
  * `A` [Binary Search Tree](src/en/data-structures/tree/binary-search-tree)
  * `A` [AVL Tree](src/en/data-structures/tree/avl-tree)
  * `A` [Red-Black Tree](src/en/data-structures/tree/red-black-tree)
  * `A` [Segment Tree](src/en/data-structures/tree/segment-tree) - with min/max/sum range queries examples
  * `A` [Fenwick Tree](src/en/data-structures/tree/fenwick-tree) (Binary Indexed Tree)
* `A` [Graph](src/en/data-structures/graph) (both directed and undirected)
* `A` [Disjoint Set](src/en/data-structures/disjoint-set)
* `A` [Bloom Filter](src/en/data-structures/bloom-filter)

## Algorithms

An algorithm is an unambiguous specification of how to solve a class of problems. It is
a set of rules that precisely define a sequence of operations.

`B` - Beginner, `A` - Advanced

### Algorithms by Topic

* **Math**
  * `B` [Bit Manipulation](src/en/algorithms/math/bits) - set/get/update/clear bits, multiplication/division by two, make negative etc.
  * `B` [Binary Floating Point](src/en/algorithms/math/binary-floating-point) - binary representation of the floating-point numbers.
  * `B` [Factorial](src/en/algorithms/math/factorial)
  * `B` [Fibonacci Number](src/en/algorithms/math/fibonacci) - classic and closed-form versions
  * `B` [Prime Factors](src/en/algorithms/math/prime-factors) - finding prime factors and counting them using Hardy-Ramanujan's theorem
  * `B` [Primality Test](src/en/algorithms/math/primality-test) (trial division method)
  * `B` [Euclidean Algorithm](src/en/algorithms/math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  * `B` [Least Common Multiple](src/en/algorithms/math/least-common-multiple) (LCM)
  * `B` [Sieve of Eratosthenes](src/en/algorithms/math/sieve-of-eratosthenes) - finding all prime numbers up to any given limit
  * `B` [Is Power of Two](src/en/algorithms/math/is-power-of-two) - check if the number is power of two (naive and bitwise algorithms)
  * `B` [Pascal's Triangle](src/en/algorithms/math/pascal-triangle)
  * `B` [Complex Number](src/en/algorithms/math/complex-number) - complex numbers and basic operations with them
  * `B` [Radian & Degree](src/en/algorithms/math/radian) - radians to degree and backwards conversion
  * `B` [Fast Powering](src/en/algorithms/math/fast-powering)
  * `B` [Horner's method](src/en/algorithms/math/horner-method) - polynomial evaluation
  * `B` [Matrices](src/en/algorithms/math/matrix) - matrices and basic matrix operations (multiplication, transposition, etc.)
  * `B` [Euclidean Distance](src/en/algorithms/math/euclidean-distance) - distance between two points/vectors/matrices
  * `A` [Integer Partition](src/en/algorithms/math/integer-partition)
  * `A` [Square Root](src/en/algorithms/math/square-root) - Newton's method
  * `A` [Liu Hui π Algorithm](src/en/algorithms/math/liu-hui) - approximate π calculations based on N-gons
  * `A` [Discrete Fourier Transform](src/en/algorithms/math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up
* **Sets**
  * `B` [Cartesian Product](src/en/algorithms/sets/cartesian-product) - product of multiple sets
  * `B` [Fisher–Yates Shuffle](src/en/algorithms/sets/fisher-yates) - random permutation of a finite sequence
  * `A` [Power Set](src/en/algorithms/sets/power-set) - all subsets of a set (bitwise and backtracking solutions)
  * `A` [Permutations](src/en/algorithms/sets/permutations) (with and without repetitions)
  * `A` [Combinations](src/en/algorithms/sets/combinations) (with and without repetitions)
  * `A` [Longest Common Subsequence](src/en/algorithms/sets/longest-common-subsequence) (LCS)
  * `A` [Longest Increasing Subsequence](src/en/algorithms/sets/longest-increasing-subsequence)
  * `A` [Shortest Common Supersequence](src/en/algorithms/sets/shortest-common-supersequence) (SCS)
  * `A` [Knapsack Problem](src/en/algorithms/sets/knapsack-problem) - "0/1" and "Unbound" ones
  * `A` [Maximum Subarray](src/en/algorithms/sets/maximum-subarray) - "Brute Force" and "Dynamic Programming" (Kadane's) versions
  * `A` [Combination Sum](src/en/algorithms/sets/combination-sum) - find all combinations that form specific sum
* **Strings**
  * `B` [Hamming Distance](src/en/algorithms/string/hamming-distance) - number of positions at which the symbols are different
  * `B` [Palindrome](src/en/algorithms/string/palindrome) - check if the string is the same in reverse
  * `A` [Levenshtein Distance](src/en/algorithms/string/levenshtein-distance) - minimum edit distance between two sequences
  * `A` [Knuth–Morris–Pratt Algorithm](src/en/algorithms/string/knuth-morris-pratt) (KMP Algorithm) - substring search (pattern matching)
  * `A` [Z Algorithm](src/en/algorithms/string/z-algorithm) - substring search (pattern matching)
  * `A` [Rabin Karp Algorithm](src/en/algorithms/string/rabin-karp) - substring search
  * `A` [Longest Common Substring](src/en/algorithms/string/longest-common-substring)
  * `A` [Regular Expression Matching](src/en/algorithms/string/regular-expression-matching)
* **Searches**
  * `B` [Linear Search](src/en/algorithms/search/linear-search)
  * `B` [Jump Search](src/en/algorithms/search/jump-search) (or Block Search) - search in sorted array
  * `B` [Binary Search](src/en/algorithms/search/binary-search) - search in sorted array
  * `B` [Interpolation Search](src/en/algorithms/search/interpolation-search) - search in uniformly distributed sorted array
* **Sorting**
  * `B` [Bubble Sort](src/en/algorithms/sorting/bubble-sort)
  * `B` [Selection Sort](src/en/algorithms/sorting/selection-sort)
  * `B` [Insertion Sort](src/en/algorithms/sorting/insertion-sort)
  * `B` [Heap Sort](src/en/algorithms/sorting/heap-sort)
  * `B` [Merge Sort](src/en/algorithms/sorting/merge-sort)
  * `B` [Quicksort](src/en/algorithms/sorting/quick-sort) - in-place and non-in-place implementations
  * `B` [Shellsort](src/en/algorithms/sorting/shell-sort)
  * `B` [Counting Sort](src/en/algorithms/sorting/counting-sort)
  * `B` [Radix Sort](src/en/algorithms/sorting/radix-sort)
* **Linked Lists**
  * `B` [Straight Traversal](src/en/algorithms/linked-list/traversal)
  * `B` [Reverse Traversal](src/en/algorithms/linked-list/reverse-traversal)
* **Trees**
  * `B` [Depth-First Search](src/en/algorithms/tree/depth-first-search) (DFS)
  * `B` [Breadth-First Search](src/en/algorithms/tree/breadth-first-search) (BFS)
* **Graphs**
  * `B` [Depth-First Search](src/en/algorithms/graph/depth-first-search) (DFS)
  * `B` [Breadth-First Search](src/en/algorithms/graph/breadth-first-search) (BFS)
  * `B` [Kruskal’s Algorithm](src/en/algorithms/graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * `A` [Dijkstra Algorithm](src/en/algorithms/graph/dijkstra) - finding the shortest paths to all graph vertices from single vertex
  * `A` [Bellman-Ford Algorithm](src/en/algorithms/graph/bellman-ford) - finding the shortest paths to all graph vertices from single vertex
  * `A` [Floyd-Warshall Algorithm](src/en/algorithms/graph/floyd-warshall) - find the shortest paths between all pairs of vertices
  * `A` [Detect Cycle](src/en/algorithms/graph/detect-cycle) - for both directed and undirected graphs (DFS and Disjoint Set based versions)
  * `A` [Prim’s Algorithm](src/en/algorithms/graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * `A` [Topological Sorting](src/en/algorithms/graph/topological-sorting) - DFS method
  * `A` [Articulation Points](src/en/algorithms/graph/articulation-points) - Tarjan's algorithm (DFS based)
  * `A` [Bridges](src/en/algorithms/graph/bridges) - DFS based algorithm
  * `A` [Eulerian Path and Eulerian Circuit](src/en/algorithms/graph/eulerian-path) - Fleury's algorithm - Visit every edge exactly once
  * `A` [Hamiltonian Cycle](src/en/algorithms/graph/hamiltonian-cycle) - Visit every vertex exactly once
  * `A` [Strongly Connected Components](src/en/algorithms/graph/strongly-connected-components) - Kosaraju's algorithm
  * `A` [Travelling Salesman Problem](src/en/algorithms/graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
* **Cryptography**
  * `B` [Polynomial Hash](src/en/algorithms/cryptography/polynomial-hash) - rolling hash function based on polynomial
  * `B` [Rail Fence Cipher](src/en/algorithms/cryptography/rail-fence-cipher) - a transposition cipher algorithm for encoding messages
  * `B` [Caesar Cipher](src/en/algorithms/cryptography/caesar-cipher) - simple substitution cipher
  * `B` [Hill Cipher](src/en/algorithms/cryptography/hill-cipher) - substitution cipher based on linear algebra
* **Machine Learning**
  * `B` [NanoNeuron](https://github.com/trekhleb/nano-neuron) - 7 simple JS functions that illustrate how machines can actually learn (forward/backward propagation)
  * `B` [k-NN](src/en/algorithms/ml/knn) - k-nearest neighbors classification algorithm
  * `B` [k-Means](src/en/algorithms/ml/k-means) - k-Means clustering algorithm
* **Image Processing**
  * `B` [Seam Carving](src/en/algorithms/image-processing/seam-carving) - content-aware image resizing algorithm
* **Statistics**
  * `B` [Weighted Random](src/en/algorithms/statistics/weighted-random) - select the random item from the list based on items' weights
* **Evolutionary algorithms**
  * `A` [Genetic algorithm](https://github.com/trekhleb/self-parking-car-evolution) - example of how the genetic algorithm may be applied for training the self-parking cars
* **Uncategorized**
  * `B` [Tower of Hanoi](src/en/algorithms/uncategorized/hanoi-tower)
  * `B` [Square Matrix Rotation](src/en/algorithms/uncategorized/square-matrix-rotation) - in-place algorithm
  * `B` [Jump Game](src/en/algorithms/uncategorized/jump-game) - backtracking, dynamic programming (top-down + bottom-up) and greedy examples
  * `B` [Unique Paths](src/en/algorithms/uncategorized/unique-paths) - backtracking, dynamic programming and Pascal's Triangle based examples
  * `B` [Rain Terraces](src/en/algorithms/uncategorized/rain-terraces) - trapping rain water problem (dynamic programming and brute force versions)
  * `B` [Recursive Staircase](src/en/algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top (4 solutions)
  * `B` [Best Time To Buy Sell Stocks](src/en/algorithms/uncategorized/best-time-to-buy-sell-stocks) - divide and conquer and one-pass examples
  * `A` [N-Queens Problem](src/en/algorithms/uncategorized/n-queens)
  * `A` [Knight's Tour](src/en/algorithms/uncategorized/knight-tour)

### Algorithms by Paradigm

An algorithmic paradigm is a generic method or approach which underlies the design of a class
of algorithms. It is an abstraction higher than the notion of an algorithm, just as an
algorithm is an abstraction higher than a computer program.

* **Brute Force** - look at all the possibilities and selects the best solution
  * `B` [Linear Search](src/en/algorithms/search/linear-search)
  * `B` [Rain Terraces](src/en/algorithms/uncategorized/rain-terraces) - trapping rain water problem
  * `B` [Recursive Staircase](src/en/algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top
  * `A` [Maximum Subarray](src/en/algorithms/sets/maximum-subarray)
  * `A` [Travelling Salesman Problem](src/en/algorithms/graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
  * `A` [Discrete Fourier Transform](src/en/algorithms/math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up
* **Greedy** - choose the best option at the current time, without any consideration for the future
  * `B` [Jump Game](src/en/algorithms/uncategorized/jump-game)
  * `A` [Unbound Knapsack Problem](src/en/algorithms/sets/knapsack-problem)
  * `A` [Dijkstra Algorithm](src/en/algorithms/graph/dijkstra) - finding the shortest path to all graph vertices
  * `A` [Prim’s Algorithm](src/en/algorithms/graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * `A` [Kruskal’s Algorithm](src/en/algorithms/graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
* **Divide and Conquer** - divide the problem into smaller parts and then solve those parts
  * `B` [Binary Search](src/en/algorithms/search/binary-search)
  * `B` [Tower of Hanoi](src/en/algorithms/uncategorized/hanoi-tower)
  * `B` [Pascal's Triangle](src/en/algorithms/math/pascal-triangle)
  * `B` [Euclidean Algorithm](src/en/algorithms/math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  * `B` [Merge Sort](src/en/algorithms/sorting/merge-sort)
  * `B` [Quicksort](src/en/algorithms/sorting/quick-sort)
  * `B` [Tree Depth-First Search](src/en/algorithms/tree/depth-first-search) (DFS)
  * `B` [Graph Depth-First Search](src/en/algorithms/graph/depth-first-search) (DFS)
  * `B` [Matrices](src/en/algorithms/math/matrix) - generating and traversing the matrices of different shapes
  * `B` [Jump Game](src/en/algorithms/uncategorized/jump-game)
  * `B` [Fast Powering](src/en/algorithms/math/fast-powering)
  * `B` [Best Time To Buy Sell Stocks](src/en/algorithms/uncategorized/best-time-to-buy-sell-stocks) - divide and conquer and one-pass examples
  * `A` [Permutations](src/en/algorithms/sets/permutations) (with and without repetitions)
  * `A` [Combinations](src/en/algorithms/sets/combinations) (with and without repetitions)
  * `A` [Maximum Subarray](src/en/algorithms/sets/maximum-subarray)
* **Dynamic Programming** - build up a solution using previously found sub-solutions
  * `B` [Fibonacci Number](src/en/algorithms/math/fibonacci)
  * `B` [Jump Game](src/en/algorithms/uncategorized/jump-game)
  * `B` [Unique Paths](src/en/algorithms/uncategorized/unique-paths)
  * `B` [Rain Terraces](src/en/algorithms/uncategorized/rain-terraces) - trapping rain water problem
  * `B` [Recursive Staircase](src/en/algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top
  * `B` [Seam Carving](src/en/algorithms/image-processing/seam-carving) - content-aware image resizing algorithm
  * `A` [Levenshtein Distance](src/en/algorithms/string/levenshtein-distance) - minimum edit distance between two sequences
  * `A` [Longest Common Subsequence](src/en/algorithms/sets/longest-common-subsequence) (LCS)
  * `A` [Longest Common Substring](src/en/algorithms/string/longest-common-substring)
  * `A` [Longest Increasing Subsequence](src/en/algorithms/sets/longest-increasing-subsequence)
  * `A` [Shortest Common Supersequence](src/en/algorithms/sets/shortest-common-supersequence)
  * `A` [0/1 Knapsack Problem](src/en/algorithms/sets/knapsack-problem)
  * `A` [Integer Partition](src/en/algorithms/math/integer-partition)
  * `A` [Maximum Subarray](src/en/algorithms/sets/maximum-subarray)
  * `A` [Bellman-Ford Algorithm](src/en/algorithms/graph/bellman-ford) - finding the shortest path to all graph vertices
  * `A` [Floyd-Warshall Algorithm](src/en/algorithms/graph/floyd-warshall) - find the shortest paths between all pairs of vertices
  * `A` [Regular Expression Matching](src/en/algorithms/string/regular-expression-matching)
* **Backtracking** - similarly to brute force, try to generate all possible solutions, but each time you generate next solution you test
if it satisfies all conditions, and only then continue generating subsequent solutions. Otherwise, backtrack, and go on a
different path of finding a solution. Normally the DFS traversal of state-space is being used.
  * `B` [Jump Game](src/en/algorithms/uncategorized/jump-game)
  * `B` [Unique Paths](src/en/algorithms/uncategorized/unique-paths)
  * `B` [Power Set](src/en/algorithms/sets/power-set) - all subsets of a set
  * `A` [Hamiltonian Cycle](src/en/algorithms/graph/hamiltonian-cycle) - Visit every vertex exactly once
  * `A` [N-Queens Problem](src/en/algorithms/uncategorized/n-queens)
  * `A` [Knight's Tour](src/en/algorithms/uncategorized/knight-tour)
  * `A` [Combination Sum](src/en/algorithms/sets/combination-sum) - find all combinations that form specific sum
* **Branch & Bound** - remember the lowest-cost solution found at each stage of the backtracking
search, and use the cost of the lowest-cost solution found so far as a lower bound on the cost of
a least-cost solution to the problem, in order to discard partial solutions with costs larger than the
lowest-cost solution found so far. Normally BFS traversal in combination with DFS traversal of state-space
tree is being used.

## Useful Information

### References

[▶ Data Structures and Algorithms on YouTube](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

### Big O Notation

*Big O notation* is used to classify algorithms according to how their running time or space requirements grow as the input size grows.
On the chart below you may find most common orders of growth of algorithms specified in Big O notation.

![Big O graphs](./assets/big-o-graph.png)

Source: [Big O Cheat Sheet](http://bigocheatsheet.com/).

Below is the list of some of the most used Big O notations and their performance comparisons against different sizes of the input data.

| Big O Notation | Type        | Computations for 10 elements | Computations for 100 elements | Computations for 1000 elements  |
| -------------- | ----------- | ---------------------------- | ----------------------------- | ------------------------------- |
| **O(1)**       | Constant    | 1                            | 1                             | 1                               |
| **O(log N)**   | Logarithmic | 3                            | 6                             | 9                               |
| **O(N)**       | Linear      | 10                           | 100                           | 1000                            |
| **O(N log N)** | n log(n)    | 30                           | 600                           | 9000                            |
| **O(N^2)**     | Quadratic   | 100                          | 10000                         | 1000000                         |
| **O(2^N)**     | Exponential | 1024                         | 1.26e+29                      | 1.07e+301                       |
| **O(N!)**      | Factorial   | 3628800                      | 9.3e+157                      | 4.02e+2567                      |

### Data Structure Operations Complexity

| Data Structure          | Access    | Search    | Insertion | Deletion  | Comments  |
| ----------------------- | :-------: | :-------: | :-------: | :-------: | :-------- |
| **Array**               | 1         | n         | n         | n         |           |
| **Stack**               | n         | n         | 1         | 1         |           |
| **Queue**               | n         | n         | 1         | 1         |           |
| **Linked List**         | n         | n         | 1         | n         |           |
| **Hash Table**          | -         | n         | n         | n         | In case of perfect hash function costs would be O(1) |
| **Binary Search Tree**  | n         | n         | n         | n         | In case of balanced tree costs would be O(log(n)) |
| **B-Tree**              | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Red-Black Tree**      | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **AVL Tree**            | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Bloom Filter**        | -         | 1         | 1         | -         | False positives are possible while searching |

### Array Sorting Algorithms Complexity

| Name                  | Best            | Average             | Worst               | Memory    | Stable    | Comments  |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Bubble sort**       | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Insertion sort**    | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Selection sort**    | n<sup>2</sup>   | n<sup>2</sup>       | n<sup>2</sup>       | 1         | No        |           |
| **Heap sort**         | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | 1         | No        |           |
| **Merge sort**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | n         | Yes       |           |
| **Quick sort**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n<sup>2</sup>       | log(n)    | No        | Quicksort is usually done in-place with O(log(n)) stack space |
| **Shell sort**        | n&nbsp;log(n)   | depends on gap sequence   | n&nbsp;(log(n))<sup>2</sup>  | 1         | No         |           |
| **Counting sort**     | n + r           | n + r               | n + r               | n + r     | Yes       | r - biggest number in array |
| **Radix sort**        | n * k           | n * k               | n * k               | n + k     | Yes       | k - length of longest key |

## More Information
[▶ Source Repo on Github](https://github.com/trekhleb/javascript-algorithms)

[▶ More about author on trekhleb.dev](https://trekhleb.dev)

[▶ Data Structures and Algorithms on YouTube](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

---