### Approach 1: (Brute)
Find the pivot point first, and store it inside a queue.
Now, traverse the array and push all the values smaller than pivot from the front and push values greater than pivot from the back.
This queue is the final answer, return it as a vector or array.

### Approach 2:
Create a new vector/array.
Iterate over the the given arr, store all the values lesser than the pivot.
Iterate again, store the pivot values.
Iterate again, store the values greater than the pivot.
Return this arr.