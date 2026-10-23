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

  The depth of the tree is atmost $\log_2 n$

- **2b) (1 pt)** By maintaining the heap property, where is the minimum element of
  the heap? Can we say anything about the maximum element?

  The minimum element of the heap is the root of the heap, and the max is one of the leaves.

- **4a) (1 pt)** What is the work/span of _reheapUp_($x$)?

  Work of `reheapUp`: $W(n) = O(\log n)$

  Span of `reheapUp`: $S(n) = O(\log n)$

- **4b) (1 pt)** What is the work/span of _reheapDown_($x$)?

  Work of `reheapDown`: $W(n) = O(\log n)$

  Span of `reheapDown`: $S(n) = O(\log n)$

- **6) (1 pt)** What is the work and span of `heapsort`?

  Work of `heapsort`: $W(n) = O(n \log n)$

  Span of `heapsort`: $S(n) = O(n \log n)$
