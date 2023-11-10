Running Time of Algorithms Time Complexity: The best case time complexity for this 
code is O(n) because that means we require no switches. this time complexity is achieved when
the array is already sorted and requires no switches. The reason why it is still O(n) is
because we have to check each element once to make sure it is sorted and not go into the inner loop.

The worst case time complexity for this code
is O(n^2) because that means we require the maximum number of switches. This time complexity is 
achieved when the array is reverse sorted and requires each element to be sorted. This means every time we
go into the inner loop, we need it to loop at least O(n) number of times leaving us with a O(n^2) time complexity.

Running Time of Algorithms Space Complexity: The Space complexity for this
code is O(c) because the input remains constant. This means that even though elements in the list are being shifted
around in order to sort the list, the initial list itself is unchanged.Therefore, our input remains unchanged and
we are left with a space complexity of O(c).

Defintion for Ice Cream Algorithm
The recursive definition of countPairs within the Result class calculates the quantity of unique flavor pairs with combined costs equal to a specified value 'm'. It iteratively checks flavor pairs (i, j), ensuring that i (representing the first flavor's index) is always less than j to prevent repetition. The recursion progresses by incrementing both i and j to the subsequent indices, and the memoization table stores the outcomes of intermediate problems, preventing repetitive computations. The final count is achieved by scanning through all potential starting indices for i and running the countPairs method for each pair, summing up the total valid pairs found.
