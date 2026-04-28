# 485. Max Consecutive Ones

## 🟢 Difficulty
Easy

## 📌 Problem Statement
Given a binary array `nums`, return the maximum number of consecutive `1`s in the array.

---

## 💡 Approach
We iterate through the array and keep track of:
- `cnt` → current consecutive 1s
- `maxi` → maximum consecutive 1s found so far

### Steps:
1. Traverse the array.
2. If element is `1`, increment `cnt`.
3. Update `maxi = max(maxi, cnt)`.
4. If element is `0`, reset `cnt = 0`.

---

## ⏱ Complexity
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)

---

## 🧪 Example

### Example 1:
