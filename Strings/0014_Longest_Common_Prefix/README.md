# 14. Longest Common Prefix

## Problem

Write a function to find the longest common prefix string amongst an array of strings.

If there is no common prefix, return an empty string `""`.

## Difficulty

Easy

## Topics

- String
- Array

## Approach

- Assume the first string is the initial prefix.
- Compare the prefix with each remaining string.
- While the current string does not start with the prefix, remove the last character from the prefix.
- If the prefix becomes empty, return an empty string.
- After checking all strings, return the final prefix.

## Time Complexity

**O(n × m)**

- `n` = Number of strings
- `m` = Length of the shortest string

## Space Complexity

**O(1)**

---

## Solution

See `Solution.java`.
