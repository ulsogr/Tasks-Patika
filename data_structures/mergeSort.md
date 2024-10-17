### [16,21,11,8,12,22] -> Merge Sort and Big-O Notation

- Divide the array in the middle.
```
         [16, 21, 11] | [8, 12, 22]
         |                        |
         |                        |
         |                        |
    [16] | [21, 11]           [8] | [12, 22]
    [21] | [11]              [12] | [22]
                           
Left Side  → [11, 16, 21]  Right Side → [8, 12, 22]
```
- Merge the sides 
      **[8, 11, 12, 16, 21, 22]**


***Write the Big-O notation.***
- Time Complexity: O(n log n)
- Space Complexity: O(n)