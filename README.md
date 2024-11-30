# optimal-pagereplacement
 The Optimal Page Replacement algorithm minimizes page faults by replacing the page that won’t be used for the longest time in the future. 

# Optimal Page Replacement Algorithm with Visualization

Implementation of the Optimal page replacement algorithm in Python.

## Features

- **Simulates Optimal Page Replacement**: Replaces the page that will not be used for the longest time in the future, minimizing page faults.
- **User Input**: Prompts for the number of frames and a sequence of page accesses (space-separated).
- **Visualization**: Uses **matplotlib** to illustrate the page replacement process and frame states at each step.
- **Page Fault Tracking**: Calculates and displays the total number of page faults.

## Key Functions

1. **`optimal_page_replacement(frames_count, page_sequence)`**:
   - Simulates the Optimal page replacement process by examining future page accesses.
   - Evicts the page used farthest in the future when a page fault occurs.
   - Returns the total number of page faults and the history of memory frames.

2. **`visualize_optimal(frames_count, page_sequence)`**:
   - Visualizes the frame states at each time step using **matplotlib**.
   - Includes a tabular representation of frame states with hit/miss information.

## Workflow

- **Page Hit**: Keeps the accessed page in memory.
- **Page Fault**: Replaces the page that will not be used for the longest time.

## Running the Program

1. **Dependencies**:
   - `matplotlib`
   - `pandas`

2. **Execution**:
   - Run the Python script.
   - Input the number of memory frames and a space-separated page sequence.
   - The program simulates the Optimal algorithm and generates a visualization of memory state changes.
