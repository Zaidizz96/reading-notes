## what is a linked list :

A linked list is a linear data structure that consists of a sequence of elements, where each element (node) points to the next element in the sequence. Unlike arrays, linked lists do not store elements in contiguous memory locations; instead, each node contains both the data and a reference (or pointer) to the next node in the list.

### Linked list has several advantages and usecasses:

1. Dynamic Size: Linked lists can grow or shrink dynamically, making them suitable for situations where the size of the data structure needs to change frequently.

2. Insertions and Deletions: Inserting or deleting elements in a linked list is more efficient than in arrays

3. Memory Efficiency: Linked lists use memory more efficiently than arrays, as they can allocate memory for each node separately, avoiding the need for a continuous block of memory.

---

## Big O : analysis of algorithms efficiency :

We use Big O notation to describe how an algorithm's runtime grows relative to its input size

Simplifying Complexity Analysis: Big O notation provides a simple and standardized way to talk about an algorithm's efficiency  It's like talking about the "general trend" of how an algorithm's performance changes with different input sizes.

- #### O(n) Linear Complexity: 
  An algorithm with O(n) complexity has a runtime that grows linearly with the input size. This means that if the input size doubles, the runtime will also roughly double.

- ####  O(1) Constant Complexity: 
  An algorithm with O(1) complexity has a constant runtime regardless of the input size. This is the best-case scenario because the algorithm's performance doesn't change as the input grows.

- #### O(n^2) Quadratic Complexity:
  Algorithms with O(n^2) complexity have runtimes that grow quadratically with the input size (exponantiol relation)

- #### Worst-Case Analysis O(n):
  Big O notation usually describes the upper bound or worst-case runtime of an algorithm. It tells us that the algorithm will perform at least as well as the stated complexity, even in the worst situations.