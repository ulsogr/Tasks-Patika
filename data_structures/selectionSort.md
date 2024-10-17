## [22,27,16,2,18,6] -> Insertion Sort 

- 22 --> 
- 22 27 --> 
- 16 22 27 --> 
- 2 16 22 27 --> 
- 2 16 18 22 27 -->
- 2 6 16 18 22 27 --> FINAL SORTED ARRAY.

### Write the Big-O notation.

1. Step --> n 
2. Step --> n-1 
3. Step -- n-2 
4. ... 
5. .. 
6. .  

` 0 + 1 + 2 + ... + (n-1) ≈ (n * (n - 1)) / 2  =  O(n²) `

### After the array is sorted, which case does the number 18 fall under? Write it down.

In this case, the number 18 falls into the ***average case*** because it is located near the middle of the array.
Because the average case is when the number is in the middle or near the middle of the array.


### [7,3,5,8,2,9,4,15,6] Write the first 4 steps, according to Selection Sort.

1. [2, 3, 5, 8, 7, 9, 4, 15, 6] -> The smallest element is 2. We replace 2 with 7.
2. [2, 3, 5, 8, 7, 9, 4, 15, 6] -> Find the smallest element in remaining array. The smallest element is 3. 3 remains in place.
3. [2, 3, 4, 8, 7, 9, 5, 15, 6] -> and again find the smallest.The smalles element is 4. We replace 4 with 5.
4. [2, 3, 4, 5, 7, 9, 8, 15, 6] -> The smallest element is 5 in remaning array. We replace 5 with 8. 

