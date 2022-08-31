# Replace-Loops-using-Recursion
Replace Loops using Recursion
Code Explanation
The if statement checks to see if sum is evaluating the base case, n <= 0, or not. If it is, then sum returns the answer, 0 - the sum of elements from 0 to 0 inclusive. Otherwise, it recurses by evaluating a simpler function call, sum(arr, n - 1). Once that returns it adds a single array element, arr[n - 1], to it and returns that sum.
