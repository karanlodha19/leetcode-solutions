# 35. Search Insert Position
## Problem
Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be inserted to maintain the sorted order.
## Difficulty
Easy
## Topic
- Array
- Binary Search
## Approach
- Traverse the sorted array.
- If the target is found, return its index.
- If the current element is greater than the target, return the current index.
- If the target is greater than all elements, return the array length.
## Time Complexity
O(n)
## Space Complexity
O(1)
## Solution
See `Solution.java`


Using Binary Search (better solution)
## Approach
- Use Binary Search on the sorted array.
- Compare the middle element with the target.
- If found, return its index.
- Otherwise, adjust the search range.
- If not found, return the insertion position (`left`).

## Time Complexity
O(log n)

## Space Complexity
O(1)
