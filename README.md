# Binary Search vs Naive Search

## Overview
This Python script demonstrates the efficiency of the binary search algorithm compared to a naive search. Binary search takes advantage of a sorted list to perform searches in **O(log n)** time complexity, whereas naive search operates in **O(n)** time complexity.

## How It Works
1. **Naive Search:** Iterates through the entire list and checks if an element matches the target.
2. **Binary Search:** Uses the divide-and-conquer approach to efficiently locate the target element in a sorted list.
3. The script compares the execution time of both search methods on a randomly generated sorted list of 10,000 elements.

## Code Structure
- `naive_search(l, target)`: Performs a linear search on the list `l` to find `target`.
- `binary_search(l, target, low, high)`: Recursively searches the sorted list `l` by halving the search space.
- The script generates a large sorted list of random numbers and times the execution of both search methods.

## Requirements
- Python 3.x
- `random` and `time` modules (built-in)

## Running the Script
Run the script using:
```sh
python binary_search.py
```
It will output the execution times for naive search and binary search.

## Example Output
```
Naive search time:  4.532 seconds
Binary search time:  0.003 seconds
```
This output shows the significant performance advantage of binary search over naive search.

## Applications
- Efficient searching in large datasets
- Used in algorithms like dictionary lookups, autocomplete, and database indexing
