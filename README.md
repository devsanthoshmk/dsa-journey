# Data structures and algorithms practice and DSA solutions for coding interview prep

This repository tracks data structures and algorithms practice across 19 topic categories. Engineers use this structured syllabus to organize DSA solutions, record practice sessions, and guide coding interview prep.

The roadmap covers foundational computer science topics ranging from elementary sorting algorithms to dynamic programming and graph traversals. The tracker records 155 specific practice problems, with 54 marked complete and 101 pending implementation.

## Repository layout

The repository maintains a single tracker file at the root.

```
dsa-journey/
  README.md
```

- `README.md` stores the topic curriculum, completion statuses, and workflow guidelines.
- Future code implementations and test files belong in dedicated language folders such as `solutions/` or `src/`.

## Setup

Clone the repository to a local workstation with Git:

```bash
git clone https://github.com/devsanthoshmk/dsa-journey.git
cd dsa-journey
```

Inspect the local repository status:

```bash
git status
```

The repository requires no external runtime, compiler, or third-party dependency to read or update the markdown tracker.

## Usage

Track problem solving progress by updating the markdown checklist directly.

1. Open `README.md` in any text editor.
2. Choose an unsolved problem from the progress checklist.
3. Implement and test the algorithm locally.
4. Change the problem item status from `- [ ]` to `- [x]`.
5. Stage, commit, and push the revision:

```bash
git add README.md
git commit -m "docs: mark problem as completed"
git push origin main
```

## Configuration

The tracking document uses standard GitHub-flavored Markdown. It requires no environment variables or configuration files.

Formatting conventions:
- File encoding: UTF-8 without byte order marks.
- Line delimiters: Unix style line feeds.
- Character style: Straight quotes with no decorative emojis or symbol substitutes.

## Progress checklist

### Sorting

- [x] Bubble sort
- [x] Selection sort
- [x] Insertion sort
- [x] Merge sort
- [x] Quick sort
- [ ] Heap sort
- [x] Counting sort
- [ ] Radix sort
- [x] Bucket sort

### Arrays

#### Easy array problems

- [x] Second largest element in an array without sorting
- [x] Check if the array is sorted and rotated
- [x] Find the kth smallest and largest element in an array
- [x] Find the largest three elements in an array
- [x] Find the first repeating element
- [x] Remove duplicates from sorted array
- [x] Left rotate an array by one place
- [x] Left rotate an array by d places
- [x] Move zeros to end
- [x] Linear search
- [x] Find the intersection
- [x] Find the union
- [x] Find missing number in an array
- [x] Maximum consecutive ones
- [x] Find the number that appears once while other numbers appear twice
- [x] Longest subarray with given sum k for positive numbers
- [x] Longest subarray with sum k for positive and negative numbers

#### Medium array problems

- [x] Two sum problem
- [x] Sort an array of zeros, ones, and twos
- [x] Majority element with more than n/2 frequency
- [x] Kadane's algorithm for maximum subarray sum
- [x] Stock buy and sell
- [x] Rearrange the array in alternating positive and negative items
- [x] Next permutation
- [x] Leaders in an array problem
- [x] Longest consecutive sequence in an array
- [x] Set matrix zeros
- [x] Rotate matrix by 90 degrees
- [x] Print the matrix in spiral manner
- [x] Count subarrays with given sum

#### Hard array problems

- [x] Pascal's triangle
- [x] Majority element with more than n/3 frequency
- [x] Three sum problem
- [x] Four sum problem
- [x] Reverse pairs
- [ ] Maximum product subarray

### Hashing

- [x] Theory
- [x] Frequently asked questions

### Binary search

#### Binary search on one-dimensional arrays

- [x] Binary search to find target value in sorted array
- [ ] Implement lower bound
- [ ] Implement upper bound
- [x] Search insert position
- [ ] Floor and ceiling in sorted array
- [ ] Find the first or last occurrence of a given number in a sorted array
- [ ] Count occurrences of a number in a sorted array with duplicates
- [ ] Search in rotated sorted array one
- [ ] Search in rotated sorted array two
- [ ] Find minimum in rotated sorted array
- [ ] Find how many times an array has been rotated
- [ ] Single element in a sorted array
- [ ] Find peak element

#### Binary search on search space answers

- [ ] Find square root of a number in logarithmic time
- [ ] Find the nth root of a number using binary search
- [ ] Koko eating bananas
- [ ] Minimum days to make m bouquets
- [ ] Find the smallest divisor
- [ ] Capacity to ship packages within d days
- [ ] Kth missing positive number
- [ ] Aggressive cows
- [ ] Book allocation problem
- [ ] Split array with largest sum
- [ ] Painter's partition
- [ ] Minimize maximum distance to gas station
- [ ] Median of two sorted arrays
- [ ] Kth element of two sorted arrays

#### Binary search on two-dimensional arrays

- [ ] Find the row with maximum number of ones
- [ ] Search in a two-dimensional matrix
- [ ] Search in a row and column sorted matrix
- [ ] Find peak element in a two-dimensional matrix
- [ ] Matrix median

### Strings

#### Basic and easy string problems

- [x] Remove outermost parentheses
- [x] Reverse words in a given string and palindrome check
- [x] Largest odd number in a string
- [x] Longest common prefix
- [x] Smallest missing integer greater than sequential prefix sum
- [x] Isomorphic string
- [x] Check whether one string is a rotation of another
- [x] Check if two strings are anagrams of each other

### Recursion

- [ ] Implementation problems
- [ ] Subsequence pattern problems
- [ ] Medium difficulty frequently asked questions
- [ ] Hard problems
- [ ] Hard difficulty frequently asked questions
- [ ] Contest problems

### Linked lists

- [ ] Fundamentals for singly linked lists
- [ ] Fundamentals for doubly linked lists
- [ ] Logic building
- [ ] Medium difficulty frequently asked questions
- [ ] Hard difficulty frequently asked questions
- [ ] Frequently asked questions for doubly linked lists
- [ ] Contest problems

### Bit manipulation

- [ ] Theory
- [ ] Problems
- [ ] Contest problems

### Greedy algorithms

- [ ] Easy problems
- [ ] Scheduling and interval problems
- [ ] Hard problems
- [ ] Contest problems

### Sliding window and two pointers

- [ ] Pattern and template
- [ ] Constant window
- [ ] Longest and smallest window problems
- [ ] Counting subarrays and substrings
- [ ] Contest problems

### Stacks and queues

- [ ] Implementation
- [ ] Monotonic stack
- [ ] Frequently asked questions
- [ ] Contest problems

### Binary trees

- [ ] Theory and traversals
- [ ] Medium problems
- [ ] Frequently asked questions
- [ ] Construction problems
- [ ] Traversal in constant space
- [ ] Contest problems

### Binary search trees

- [ ] Theory and basics
- [ ] Medium problems
- [ ] Frequently asked questions
- [ ] Contest problems

### Heaps

- [ ] Theory and implementation
- [ ] Frequently asked questions
- [ ] Contest problems

### Graphs

- [ ] Theory and traversals
- [ ] Traversal problems
- [ ] Cycles
- [ ] Hard problems part one
- [ ] Shortest path algorithms
- [ ] Minimum spanning tree
- [ ] Hard problems part two
- [ ] Additional algorithms
- [ ] Contest problems

### Dynamic programming

- [ ] Introduction
- [ ] One-dimensional dynamic programming
- [ ] Two-dimensional dynamic programming
- [ ] Dynamic programming on grids
- [ ] Dynamic programming on stocks
- [ ] Dynamic programming on subsequences
- [ ] Longest increasing subsequence
- [ ] Dynamic programming on strings
- [ ] Matrix chain multiplication dynamic programming
- [ ] Contest problems

### Tries

- [ ] Theory
- [ ] Problems

### Advanced string algorithms

- [ ] Medium problems
- [ ] Advanced or less common problems
- [ ] Contest problems

### Mathematics

- [ ] Sieve of Eratosthenes
- [ ] Contest problems
