# Leetcode Algorithm Overview Classification

## Greedy Algorithms: Heap Usage

### 1. [1642 Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/)

(Keep min queue, pop the min bricks while maintaining the ladder num) O(nlogn) O(n)

### 2. [2402 Meeting Roome 3]()

(Sort interval and Dual min pq, (endtime, idx), (idx) for simulation) O(nlogn + mlogn) O(n)

## Count Subarray By Element

### 1. [828 Count Unique Characters of All Substrings of a Given String](https://leetcode.com/problems/count-unique-characters-of-all-substrings-of-a-given-string/)

(Count the count of unique elements of each character can contribute to, (j-i) \* (k-j)) O(n) O(n)

## Deque

### 1. [1438 Longest-Continuous-Subarray-With-Absolute-Diff-Less-Than-or-Equal-to-Limit](https://leetcode.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/)

(Maintain maxDeque and minDeque, the top of each them is the maximum and minimum of the subarray. if the diff is greater than k, then moves i until move to a correct subarray) O(n) O(n)

## Graph BFS

### 1. [317 Shortest Distance From All Bulidings](https://leetcode.com/problems/shortest-distance-from-all-buildings/)

(Need to start from building then BFS to empty, otherwise will TLE. Maintain a dist and hit matrix is the key, to get the min from the dist when the hit == building_num) O(m^2 n^2) O(mn)

## Hash

### 1. [249 Group Shifted Strings](https://leetcode.com/problems/group-shifted-strings/)

(hash each word, remember the circular order, O(n\*k) O(n\*k))

## Recursion

### 1. [38 Count and Say](https://leetcode.com/problems/count-and-say/)

(Recursion + Two pointer to transfrom to the specified format) O(L1 + L2 + ... + Ln) O(n+Lmax)
