# Min-Cost Cable Merging

Computes the minimum total cost of merging a set of cables into one, where the cost of each merge equals the sum of the two cable lengths merged.

## Features

- `minimize_cost` repeatedly merges the two shortest cables using a min-heap (`heapq`) until only one remains, accumulating the total merge cost

## Technology

- Python 3

## Running

```
python task.py
```
