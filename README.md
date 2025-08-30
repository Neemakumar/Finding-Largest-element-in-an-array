🔹 Finding the Largest Element in an Array
1]The largest element in an array is the one with the maximum value among all elements.
Step 1: Assume the first element is the largest (max = arr[0]).
Step 2: Traverse the array from the second element to the last.
Step 3: For each element, compare it with max.
If the current element is greater than max, update max.
Step 4: After completing the traversal, max will store the largest element.

✅ Example
Array: [5, 8, 2, 10, 3]
Start: max = 5
Compare with 8 → update max = 8
Compare with 2 → no change
Compare with 10 → update max = 10
Compare with 3 → no change
Final Answer → 10

⏱ Complexity
Time Complexity: O(n) (only one scan of the array).
Space Complexity: O(1) (no extra space required).
