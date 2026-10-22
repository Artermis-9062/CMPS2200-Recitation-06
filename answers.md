# CMPS 2200 Recitation 06

## Answers

**Name:** Chuong Hoang Pham

---

Place all written answers from `recitation-06.md` here for easier grading.

- **1)** Before we implement a heap, let's consider if we just maintain
  an unordered list/sequence.
  - **1a) (1 pt)** What is the work/span of _deleteMin_?

  The work of `deleteMin` is $O(n)$.

  The span of `deleteMin` is $O(\log n)$
  - **1b) (1 pt)** What is the work/span of _insert(x)_?

  The work of `insert` is $O(1)$

  The span of `insert` is $O(1)$

- **2a) (1 pt)** For a heap with $n$ elements, what does this imply about the depth of the associated almost-complete binary tree?

- **2b) (1 pt)** By maintaining the heap property, where is the minimum element of
  the heap? Can we say anything about the maximum element?

- **4a) (1 pt)** What is the work/span of _reheapUp_($x$)?

- **4b) (1 pt)** What is the work/span of _reheapDown_($x$)?

- **6) (1 pt)** What is the work and span of `heapsort`?
