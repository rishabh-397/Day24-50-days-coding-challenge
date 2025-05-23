# Day24-50-days-coding-challenge
🔸 Problem 1: Basic Calculator

📌 Problem Statement:
Given a valid string expression containing digits, +, -, parentheses and spaces, evaluate it and return the result.
⚠️ No use of built-in eval() or similar functions allowed.

📌 Constraints:

1 ≤ s.length ≤ 300,000

Expression is valid and contains only +, -, (, ), and digits.

'+' cannot be unary. '-' can be unary.

📌 Approach:

Use a stack to track current results and signs when encountering (

Handle unary minus correctly by tracking the current sign

Evaluate digit by digit and apply operator logic manually

📌 Examples:
Input: "1 + 1" → Output: 2
Input: " 2-1 + 2 " → Output: 3
Input: "(1+(4+5+2)-3)+(6+8)" → Output: 23

🔸 Problem 2: Move Zeroes

📌 Problem Statement:
Given an integer array nums, move all 0s to the end in-place, maintaining the relative order of the non-zero elements.

📌 Constraints:

1 ≤ nums.length ≤ 10⁴

−2³¹ ≤ nums[i] ≤ 2³¹ − 1

Do not use an additional array.

📌 Approach:

Use two pointers: one to track position for the next non-zero element, and the other to iterate over the array.

Swap elements in-place to move non-zero values forward and fill the rest with 0s.

📌 Examples:
Input: [0,1,0,3,12] → Output: [1,3,12,0,0]
Input: [0] → Output: [0]

Topics Covered:

Stack

Expression Parsing

Two Pointers

In-place Operations
