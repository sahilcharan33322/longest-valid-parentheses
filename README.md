An efficient implementation to find the length of the longest valid (well-formed) parentheses substring.

Complexity Analysis
-Time Complexity: $O(n)$ — The string is traversed exactly twice (left-to-right and right-to-left), ensuring linear runtime efficiency.
-Space Complexity: $O(1)$ — The algorithm uses only a few integer counters, ensuring optimal memory consumption without requiring stacks or extra data structures.

Algorithm Overview
The solution utilizes a two-pass scanning approach to keep track of the count of open `(` and close `)` brackets. By performing the check from both directions, it accurately captures all valid substrings, even those with unbalanced prefixes or suffixes.
