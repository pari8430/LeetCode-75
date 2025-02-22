# 1. Merge Strings Alternately (Leetcode 1768)

## Problem Statement

Given two strings `word1` and `word2`, merge them by adding letters in alternating order, starting with `word1`. If one string is longer than the other, append the additional letters at the end.

### Example 1:
Input: word1 = "abc", word2 = "pqr" Output: "apbqcr"

### Example 2:
Input: word1 = "ab", word2 = "pqrs" Output: "apbqrs"

### Example 3:
Input: word1 = "abcd", word2 = "pq" Output: "apbqcd"


---

## Solution Approach

This solution follows:
- **Using StringBuilder** for efficient string concatenation.
- **Looping through the minimum length** of the two strings to merge characters alternately.
- **Appending the remaining characters** from the longer string.

## Complexity Analysis
Time Complexity: O(N + M) (where N and M are lengths of word1 and word2 respectively)
Space Complexity: O(N + M) (for storing the merged string in StringBuilder)

## Edge Cases Considered
✔️ Strings of equal length
✔️ word1 is longer than word2
✔️ word2 is longer than word1
✔️ Strings with a single character

## Summary
This problem was solved using StringBuilder for efficiency and a loop to merge characters alternately. The final approach avoids unnecessary variables and provides an optimal solution.

Hope this helps! 🚀


