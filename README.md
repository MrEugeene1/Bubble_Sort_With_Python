# Bubble Sort (Python)

A clean, beginner-friendly implementation of the Bubble Sort algorithm in Python.

This script:
- Accepts a user-defined number of elements.
- Reads numeric input values from the console.
- Sorts the list in ascending order using Bubble Sort.
- Prints the sorted result and the number of swaps performed.

## Why This Project

Bubble Sort is one of the best algorithms for learning core programming concepts:
- Loops and iteration
- Conditionals and comparisons
- In-place list manipulation (swapping)
- Basic algorithm analysis

Even though Bubble Sort is not efficient for large datasets, it is excellent for building algorithmic intuition.

## Project Structure

```
.
|-- bubbleSort.py
|-- README.md
```

## Requirements

- Python 3.x

## How to Run

From the project directory, execute:

```bash
py bubbleSort.py
```

You will be prompted to:
1. Enter the number of elements.
2. Enter each list element.

## Example Run

```text
How many elements do you want to sort: 5
Enter a list element: 6
Enter a list element: 2
Enter a list element: 9
Enter a list element: 1
Enter a list element: 4

Sorted:
[1.0, 2.0, 4.0, 6.0, 9.0]
6 comparisons
```

Note: In the current script, the displayed count is incremented when a swap happens, so the value represents swaps, not all comparisons.

## Algorithm Summary

Bubble Sort repeatedly compares adjacent items and swaps them when they are in the wrong order. The process continues until one full pass completes with no swaps.

## Time and Space Complexity

- Best case: O(n) when the list is already sorted (thanks to early stop)
- Average case: O(n^2)
- Worst case: O(n^2)
- Space: O(1) extra space (in-place sorting)

## Suggested Improvements

- Rename the output label from `comparisons` to `swaps` for accuracy.
- Move logic into reusable functions for easier testing.
- Add input validation and exception handling.
- Add unit tests for edge cases (empty list, duplicates, negatives, already sorted).

## License

This project is open for educational and personal use.

