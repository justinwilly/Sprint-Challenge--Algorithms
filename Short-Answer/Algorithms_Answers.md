#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
    just one loop: a increases at the same rate with each iteration


b) O(n log(n))
    The outer loop increments linearly at the same rate -- O(n)
    The inner loop doubles the index with each iteration -- O(log(n))
    Since the loops are nested, we multiply them resulting in a time complexity of O(n log(n))

c) O(n)
    recursion, but increases at a rate of two with each input

## Exercise II
1. Find the middle floor of the building and drop an egg. (Binary search)
    --if the egg breaks, we know that the value of 'F' is either this floor or a floor below(thus we can eliminate the floors above)
    --if the egg doesn't break, we know that the value of 'F' is higher than this floor (thus we can eliminate all the floors below)

2. We'll continue the process described in step 1 (eliminating half the floors) until we find the lowest floor where the egg breaks (F)

--> this should produce a runtime complexity of O(log n)

