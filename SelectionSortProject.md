# [22,27,16,2,18,6] -> Selection Sort

- Step 1: [22, 27, 16, 2, 18, 6]
In the first step, the array is already considered partially sorted since the first element is alone. So, we can say that the first step is the initial state of the array.

- Step 2: [22, 27, 16, 2, 18, 6]
In the second step, we compare the second element (27) with the first element (22). Since 27 is greater than 22, no swapping is needed, and the array remains the same.

- Step 3: [16, 22, 27, 2, 18, 6]
In the third step, we compare the third element (16) with the previous elements (27 and 22). Since 16 is smaller, we shift 27 and 22 to the right, and insert 16 in its correct position.

- Step 4: [2, 16, 22, 27, 18, 6]
In the fourth step, we compare the fourth element (2) with the previous elements (27, 22, and 16). Since 2 is smaller, we shift 27, 22, and 16 to the right, and insert 2 in its correct position.

- Step 5: [2, 16, 18, 22, 27, 6]
In the fifth step, we compare the fifth element (18) with the previous elements (27, 22, and 16). Since 18 is greater than 16 and smaller than 22, no more shifting is needed, and we insert 18 in its correct position.

- Step 6: [2, 6, 16, 18, 22, 27]
In the final step, we compare the sixth element (6) with the previous elements (27, 22, 18, and 16). Since 6 is smaller, we shift 27, 22, 18, and 16 to the right, and insert 6 in its correct position.

- The sorted array using Insertion Sort is [2, 6, 16, 18, 22, 27] 

- The Big-O notation for the given array [22, 27, 16, 2, 18, 6] in the context of Insertion Sort is O(n^2).

---
The time complexity of Insertion Sort for the given array [22, 27, 16, 2, 18, 6] is O(n^2). After the array is sorted, the position of the number 18 falls into the Average case scenario.

 Average case scenario: The average case refers to the situation where the target number is located somewhere in the middle of the sorted array. In this case, the algorithm would need to traverse through a portion of the array to find the target number.
 
 ---
 
# [7,3,5,8,2,9,4,15,6] -> Selection Sort(first four steps)

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
