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
