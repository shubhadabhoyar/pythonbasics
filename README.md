# pythonbasics

A hands-on Jupyter Notebook that goes from core Python syntax to data structures and classic algorithms, the material of an introductory Data Structures & Algorithms (DSA) course.

**Notebook:** [`python_fundamentals_dsa.ipynb`](python_fundamentals_dsa.ipynb)

## What's inside

| Module | Topics | Practice exercises |
| --- | --- | --- |
| 1. Python fundamentals | Types and casting, operators, strings, control flow, functions, comprehensions, classes, exceptions | `fizz_buzz`, `is_palindrome`, `word_frequencies` |
| 2. Linear data structures | Lists, dicts, sets, stacks, queues (`deque`), singly linked lists | `two_sum`, `has_cycle` |
| 3. Non-linear data structures | Binary search trees and traversals, heaps (`heapq`), graphs as adjacency lists | `max_depth`, `is_valid_bst` |
| 4. Algorithms and Big-O | Binary search, insertion/merge/quick sort, BFS and DFS, dynamic programming | `first_bad_version`, `coin_change` |

Every practice exercise is solved in place, with comments and `assert` tests that print "all tests passed" when the cell runs. An appendix at the end has a second set of reference solutions with their own checks.

## How to run it

You need Python 3.9 or newer and Jupyter. The notebook uses only the standard library, so nothing else needs installing.

```bash
pip install notebook
jupyter notebook python_fundamentals_dsa.ipynb
```

Then choose **Run → Run All Cells**, or step through with **Shift + Enter**. Run the cells from top to bottom, because later sections reuse classes and data built earlier (for example `ListNode`, `TreeNode`, `bst_root` and `graph`).

## Status

All 21 code cells run without errors on Python 3.9 and Python 3.14, and every exercise test passes.
