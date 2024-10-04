# Merge Sort

## Description

This project implements the Merge Sort algorithm, a classic sorting technique that divides the array into halves, sorts each half recursively, and then merges the sorted halves back together. The main advantage of Merge Sort is its predictable O(n log n) time complexity, making it efficient for larger datasets.

## Features

- **Recursive Sorting:** Divides the array into two halves and sorts each half recursively.
- **Merge Operation:** Merges the sorted halves back into a single sorted array.
- **Stable Sort:** Maintains the relative order of equal elements, making it ideal for datasets with multiple identical values.

## How It Works

A step-by-step explanation of how the Merge Sort algorithm operates:

1. **Input:** The program takes an unsorted array as input.
2. **Divide:** Splits the array into two halves until each subarray contains a single element.
3. **Conquer:** Recursively sorts each subarray.
4. **Combine:** Merges the sorted subarrays back together to form a fully sorted array.
5. **Output:** Returns the sorted array as the final output.

## Usage

### Prerequisites

- Python 3.x

### Running the Program

1. Clone the repository or download the script file `Merge_Sort.py`.
2. Run the script using the command:

    ```bash
    python Merge_Sort.py
    ```

3. The program will print the sorted array as shown in the example below.

### Example

```bash
$ python Merge_Sort.py

Sorted array is: [5, 6, 7, 11, 12, 13]
```
## Program Structure

- **`merge_sort(arr)`:** Recursively divides and sorts the input array `arr`.
- **`main()`:** Example usage of the `merge_sort` function with a sample array.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


