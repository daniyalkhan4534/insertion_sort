# insertion_sort

A straightforward sorting technique called insertion sort divides an array into two sections: one that is sorted and the other that is not. All of the members of the array are initially present in the unsorted section, which is initially empty. The smallest element from the unsorted section is chosen for each algorithm iteration and placed in the appropriate location in the sorted component. The algorithm operates by iteratively traversing the array, selecting one element, and comparing it to the portion of the array that has already been sorted. The element is inserted into the proper position in the sorted portion if it is smaller than the element in the sorted part. Up till the full array is sorted, this procedure is repeated. The time for Insertion Sort is.

Algorithm :
The algorithm works as follows:

Iterate through the array from index 1 to size-1.
For each index i, pick the element at index i and store it in a variable called small.
Iterate backwards from index i-1 to 0 and compare each element with small.
If an element is greater than small, shift it one position to the right.
When an element smaller than or equal to small is found, insert small at the next position.
![image](https://user-images.githubusercontent.com/127819492/234487614-344a1193-fdbc-465e-a216-343ce7f8fa45.png)

Example
Suppose we have an unsorted array of integers: arr = {32, 5, 7, 3, 6}. After applying Insertion Sort, the sorted array would be: arr = {3, 5, 6, 7, 32}.

Uses
Insertion Sort is useful for sorting small arrays or partially sorted arrays. It has a time complexity of O(n^2) and is not suitable for sorting large arrays.

Applications:
Insertion Sort can be used in situations where the input size is small and the array is almost sorted or the input array is guaranteed to have only a few inversions. It is often used as a subroutine in more complex sorting algorithms like Quick Sort, Merge Sort, and Shell Sort.
