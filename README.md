# Longest Valid Parentheses

## Problem Statement

Given a string containing only the characters `(` and `)`, return the length of the longest valid (well-formed) parentheses substring.

## Input Format

- A single string `s` containing only `(` and `)`.

## Output Format

- Print a single integer representing the length of the longest valid parentheses substring.

## Example 1

### Input
```text
(()
```

### Output
```text
2
```

### Explanation
The longest valid parentheses substring is `()`.

---

## Example 2

### Input
```text
)()())
```

### Output
```text
4
```

### Explanation
The longest valid parentheses substring is `()()`.

---

## Example 3

### Input
```text

```

### Output
```text
0
```

### Explanation
The input string is empty, so there are no valid parentheses.

---

## Constraints

- `0 <= s.length <= 3 × 10^4`
- `s[i]` is either `'('` or `')'`

## Time Complexity

- **O(n)**

## Space Complexity

- **O(n)**
