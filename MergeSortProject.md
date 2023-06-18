# [16,21,11,8,12,22] -> Merge Sort

**_[16, 21, 11] array:_**

- First, it is divided into two halves: [16] | [21, 11].
- Then, the subarrays are further divided: [21] | [11].
- Finally, the elements are merged in sorted order: [11, 16, 21].


**_[8, 12, 22] array:_**

- First, it is divided into two halves: [8] | [12, 22].
- Then, the subarrays are further divided: [12] | [22].
- Finally, the elements are merged in sorted order: [8, 12, 22].

**_ Lastly, the arrays [11, 16, 21] and [8, 12, 22] are merged:_**

- They are merged as follows: [11, 16, 21] | [8, 12, 22].
- The final result is a sorted array: [8, 11, 12, 16, 21, 22].

---
# Big O Notation

- The Big-O notation for the given array [16, 21, 11, 8, 12, 22] in the context of Merge Sort is O(n log n).
- Merge Sort has a time complexity of O(n log n), which means that its time requirement grows in proportion to the size of the input array, multiplied by the logarithm of the size of the input array. This makes Merge Sort an efficient sorting algorithm for large datasets. It achieves this efficiency by recursively dividing the array into smaller subarrays, sorting them individually, and then merging them back together in a sorted manner.
