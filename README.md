# Odd Even Linked List

## Problem Description

Given the `head` of a **singly linked list**, group all the nodes with **odd indices** together followed by the nodes with **even indices**, and return the **reordered list**.

- The **first node** is considered **odd**, the **second** is **even**, and so on.
- The **relative order** inside both the odd and even groups should **remain the same** as in the input.

You must solve the problem with:

- **O(1)** extra space complexity  
- **O(n)** time complexity

---

## Examples

### Example 1:

**Input:**  
`head = [1,2,3,4,5]`  

**Output:**  
`[1,3,5,2,4]`  

---

### Example 2:

**Input:**  
`head = [2,1,3,5,6,4,7]`  

**Output:**  
`[2,3,6,7,1,5,4]`  

---

## Constraints

* The number of nodes in the linked list is in the range `[0, 10⁴]`  
* `-10⁶ <= Node.val <= 10⁶`

---
