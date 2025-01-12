### Approach 1:
Take two pointers starting from 0 and 1.
Iterate over the array, push even values to the first/even pointer, and push odd values to the second/odd pointer.
Return the new array.

### Approach 2: (Less space)
Take two pointers starting from 0 and 1.
Iterate over the array until you find mismatch between the array values and the index. Stop as soon as you find the mismatch.
From here, start swapping and incrementing the index by 2.
Return the original array.