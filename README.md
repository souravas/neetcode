# neetcode

neetcode is a personal collection of algorithm and data-structure solutions (LeetCode-style), implemented in Python and organized by topic.

## What this repository contains

- Topic-based folders (arrays_hashes, backtracking, binary_search, heap, linked_list, sliding_window, stack, trees, two_pointers)
- Small, self-contained Python solutions to common interview problems

See the top-level folders for individual problem files. Each file typically contains one solution (a function or class) and may include a short example or helper code.

## Requirements

- Python 3.8+

No external dependencies are required by default. If a specific problem needs a third-party package, it will be noted in that problem's file.

## Quick usage

Run a solution file directly with Python (if it includes runnable example code):

```zsh
python3 arrays_hashes/two_sum.py
```

Or import a function from a module in another script or REPL:

```zsh
python3 -c "from arrays_hashes.two_sum import two_sum; print(two_sum([2,7,11,15], 9))"
```

## Project structure (high level)

- arrays_hashes/     — array and hash-table problems
- backtracking/      — backtracking and recursion
- binary_search/     — binary search patterns
- heap/              — heap / priority-queue problems
- linked_list/       — linked list problems and utilities
- sliding_window/    — sliding window techniques
- stack/             — stack-related problems
- trees/             — binary tree problems and helpers
- two_pointers/      — two-pointer patterns

## Contributing

Contributions are welcome. Small improvements (bug fixes, improved solutions, docstrings, type hints, or tests) are encouraged. Open a pull request with a brief description of the change and the problem/file it targets.

## License

This repository is provided under the terms of the LICENSE file in this repo.

---
If you'd like, I can also add: a CONTRIBUTING.md, basic tests for a few problems, or a small Makefile/Taskfile for running quick checks — tell me which and I'll add them.