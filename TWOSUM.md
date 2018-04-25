The problem is to find the index of 2 elements in a sorted array whose sum is a targetSum specified.
One way to solve this is using the 2 pointer technique. 
the first pointer starts at the first element of the array and the second pointer is at the last element of the array.
We check the sum of the elements at these pointer indexes and check if they add up to the target sum. If they do then we return an array with the 2 pointer values.
If the sum is less than the target sum then we move the first pointer forward and repeat the previous step.
If the sum is more than the target sum then we move the second pointer backwards and then check the sum of the elements at the new indexes.
We repeat the previous 3 steps till the first pointer index is less than the second pointer index.
If we dont find the elements which add up to the target sum, we return an empty array. This is a O(n) time complexity solution.

Another way to solve this problem is using a hashmap. 
We can add each element to a hashmap with the element as the key and its index as the value.
As we are adding an element, we check the hashmap to see if there exists another element in the hashmap with key = targetSum - element.
If we find it we return an array with index of the element we found and the current element index.
This is a O(n) time complexity solution, but has additional space complexity the Hashmap which would be O(n).
