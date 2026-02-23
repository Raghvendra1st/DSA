# ✅ Day 1 – Arrays Basics

### 1) Two Sum

**Problem:** Given an array and a target, return indices of two numbers that add up to the target.
**What it teaches:** HashMap for O(n) lookup instead of brute force O(n²).
**Core idea:** Store visited numbers in a map.

---

### 2) Best Time to Buy and Sell Stock

**Problem:** Given daily stock prices, find the maximum profit from one buy and one sell.
**What it teaches:** Tracking minimum value while scanning.
**Core idea:** Keep minimum price so far, update max profit.

---

### 3) Contains Duplicate

**Problem:** Return true if any value appears at least twice.
**What it teaches:** Set usage for quick duplicate detection.
**Core idea:** If number already in set → duplicate.

---

# ✅ Day 2 – Strings + Two Pointers

### 4) Valid Anagram

**Problem:** Check if two strings contain the same characters in different order.
**What it teaches:** Frequency counting.
**Core idea:** Count characters using array or hashmap.

---

### 5) Valid Palindrome

**Problem:** Check if a string is a palindrome ignoring spaces and special characters.
**What it teaches:** Two-pointer string scanning.
**Core idea:** Move left/right pointers inward.

---

### 6) Move Zeroes

**Problem:** Move all zeroes to the end without changing order of other elements.
**What it teaches:** Two-pointer array manipulation.
**Core idea:** Slow pointer tracks position of next non-zero.

---

# ✅ Day 3 – Sliding Window

### 7) Longest Substring Without Repeating Characters

**Problem:** Find the length of the longest substring without repeating characters.
**What it teaches:** Sliding window with set/map.
**Core idea:** Expand right pointer, shrink left when duplicate appears.

---

### 8) Maximum Average Subarray I

**Problem:** Find maximum average of subarray of size k.
**What it teaches:** Fixed-size sliding window.
**Core idea:** Maintain window sum while sliding.

---

### 9) Subarray Sum Equals K

**Problem:** Count number of subarrays whose sum equals k.
**What it teaches:** Prefix sum + hashmap trick.
**Core idea:** If prefixSum - k exists → valid subarray.

---

# ✅ Day 4 – Hashing / Frequency

### 10) Group Anagrams

**Problem:** Group words that are anagrams.
**What it teaches:** Using sorted string or frequency as hashmap key.
**Core idea:** Words with same sorted form go together.

---

### 11) Top K Frequent Elements

**Problem:** Return k most frequent elements.
**What it teaches:** Frequency map + heap or bucket sort.
**Core idea:** Count first, then select top k.

---

### 12) Intersection of Two Arrays

**Problem:** Return common elements between two arrays.
**What it teaches:** Set intersection logic.
**Core idea:** Store one array in set, check in other.

---

# ✅ Day 5 – Stack

### 13) Valid Parentheses

**Problem:** Check if parentheses/brackets are properly matched.
**What it teaches:** Stack for matching pairs.
**Core idea:** Push open bracket, match with closing.

---

### 14) Daily Temperatures

**Problem:** For each day, find how many days until a warmer temperature.
**What it teaches:** Monotonic stack.
**Core idea:** Stack stores indices of decreasing temperatures.

---

### 15) Min Stack

**Problem:** Design stack that supports push, pop, top, and getMin in O(1).
**What it teaches:** Stack design with auxiliary tracking.
**Core idea:** Maintain second stack for minimums.

---

# ✅ Day 6 – Binary Search

### 16) Binary Search

**Problem:** Find target in sorted array.
**What it teaches:** Classic binary search pattern.
**Core idea:** Mid = left + (right-left)/2.

---

### 17) Search Insert Position

**Problem:** Return index if found; otherwise where it should be inserted.
**What it teaches:** Lower-bound binary search.

---

### 18) Find Peak Element

**Problem:** Find an element greater than its neighbors.
**What it teaches:** Binary search on unsorted array.
**Core idea:** Move toward increasing slope.

---

# ✅ Day 7 – Greedy + Intervals

### 19) Maximum Subarray

**Problem:** Find contiguous subarray with largest sum.
**What it teaches:** Kadane’s algorithm.
**Core idea:** Reset sum when it becomes negative.

---

### 20) Jump Game

**Problem:** Determine if you can reach the last index.
**What it teaches:** Greedy range tracking.
**Core idea:** Track farthest reachable index.

---

### 21) Merge Intervals

**Problem:** Merge overlapping intervals.
**What it teaches:** Sorting + interval merging logic.
**Core idea:** Sort by start time first.

---

# 🔥 Important

These 21 problems cover:

* Hashing
* Two Pointers
* Sliding Window
* Stack
* Binary Search
* Greedy
* Intervals


-----------
