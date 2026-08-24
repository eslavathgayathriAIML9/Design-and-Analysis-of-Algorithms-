# Design-and-Analysis-of-Algorithms-DAA 
practical-1
Summary:
Sorting is the process of arranging data in ascending or descending order. Common algorithms include Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each algorithm differs in speed, memory usage, and efficiency, making them suitable for different types of data.
Conclusion:
Sorting is an essential operation in computer science that improves data organization and searching efficiency. Choosing the right sorting algorithm depends on the size of the data, performance requirements, and application needs.

practical-2
summary:
Linear Search and Binary Search are searching techniques used to find a particular element in a list. Linear Search checks elements one by one from the beginning until the required element is found. Binary Search repeatedly divides a sorted list into two halves and searches only the half where the element may exist.

Search Method	Time Complexity	Space Complexity	Requirement
Linear Search	O(n)	O(1)	List need not be sorted
Binary Search	O(log n)	O(1) iterative	List must be sorted

Conclusion:
Linear Search is simple and can be used on both sorted and unsorted data, but it can be slower for large datasets. Binary Search is much faster for large sorted datasets because it eliminates half of the search space in every step. Therefore, Binary Search is more efficient than Linear Search when the data is sorted, while Linear Search is preferable when the data is unsorted or the dataset is small.

practical-3
Summary:
Heap Sort is a comparison-based sorting algorithm that uses a binary heap data structure. It first builds a max heap from the given elements. Then, it repeatedly removes the largest element from the heap and places it at the end of the array. This process continues until the entire array is sorted.

Best Time Complexity: O(n log n)
Average Time Complexity: O(n log n)
Worst Time Complexity: O(n log n)
Space Complexity: O(1)
It is an in-place sorting algorithm.
It does not require extra arrays for sorting.

Conclusion:
Heap Sort is an efficient and reliable sorting algorithm with a worst-case time complexity of O(n log n). It performs consistently even when the input data is already sorted or arranged in an unfavorable order. Although Heap Sort is generally not stable and can be less practical than Quick Sort in some cases, its guaranteed O(n log n) performance and O(1) extra space make it useful for memory-constrained applications.
