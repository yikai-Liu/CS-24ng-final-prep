# Leetcode Algorithm Overview Classification

## Greedy Algorithms: Heap Usage

### 1. [1642 Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/)

(Keep min queue, pop the min bricks while maintaining the ladder num) (O(nlogn) O(n))

## Count Subarray By Element

### 1. [828 Count Unique Characters of All Substrings of a Given String](https://leetcode.com/problems/count-unique-characters-of-all-substrings-of-a-given-string/)

(Count the count of unique elements of each character can contribute to, (j-i) \* (k-j)) (O(n) O(n))

## Graph BFS

### 1. [317 Shortest Distance From All Bulidings](https://leetcode.com/problems/shortest-distance-from-all-buildings/)

(Need to start from building then BFS to empty, otherwise will TLE. Maintain a dist and hit matrix is the key, to get the min from the dist when the hit == building_num) O(m^2 n^2) O(mn)
