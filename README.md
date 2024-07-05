# SelectionSort
Selection sort is straightforward to implement but inefficient for large datasets compared to more advanced sorting algorithms like quicksort or mergesort.


Selection sort is a simple comparison-based sorting algorithm. Here's a brief overview of how it works and its time and space complexity:

### How Selection Sort Works:
1. **Concept**: Selection sort works by dividing the input list into two parts: the sorted sublist and the unsorted sublist. Initially, the sorted sublist is empty, and the unsorted sublist is the entire input list.
  
2. **Operation**:
   - It repeatedly selects the smallest (or largest, depending on the sorting order) element from the unsorted sublist.
   - Swap it with the leftmost unsorted element, effectively growing the sorted sublist by one element.
   - This process is repeated until the entire list is sorted.

### Time Complexity:
- **Worst-case time complexity**: \( O(n^2) \)
- **Best-case time complexity**: \( O(n^2) \)
- **Average-case time complexity**: \( O(n^2) \)

In all cases (best, worst, average), selection sort requires \( O(n^2) \) comparisons to sort \( n \) items. This is because it always iterates through the entire remaining unsorted sublist to find the minimum element and performs a swap.

### Space Complexity:
- **Space complexity**: \( O(1) \) 
- Selection sort is an **in-place** sorting algorithm, meaning it doesn't require any extra storage space other than the input array itself. It operates by swapping elements within the array.

### Key Points:
- Selection sort is inefficient for large lists and is generally outperformed by more advanced algorithms like quicksort, mergesort, or heapsort, which have better average and worst-case time complexities.
- It is simple to implement and useful for educational purposes due to its straightforward nature and minimal space complexity.

In summary, while selection sort is not recommended for large datasets due to its \( O(n^2) \) time complexity, it is still valuable for understanding sorting algorithms and can be practical for small lists or educational purposes.
