# 1. Two Sum

## Problem

Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to the target.

You may assume that each input has exactly one solution, and you may not use the same element twice.

---

## Difficulty

Easy

---

## Topics

- Array
- Hash Map

---

## Approach

- Create a HashMap to store each number and its index.
- Traverse the array once.
- For each element, calculate the complement (`target - nums[i]`).
- If the complement already exists in the HashMap, return the indices.
- Otherwise, store the current element and its index.

---

## Time Complexity

**O(n)**

---

## Space Complexity

**O(n)**

---

## Solution

See `Solution.java`.
