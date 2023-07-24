# Exercise

##Exercise: ft_merge_sort
Allowed functions: malloc, free

Create a function ft_merge_sort using a Divide and Conquer algorithm that sorts any given array of integers in ascending order.

The function merges two sub arrays of the given array.
- First sub array is arr[l..m]
- Second sub array is arr[m+1..r]
  
The array given as argument won’t be modifiable.

Here’s how it should be prototyped:
`void ft_merge_sort(int arr[], int l, int r);` 

The task consists of the following steps:
  1) Divide the unsorted list into n sublists, each containing one element (a list of one element is considered sorted).
  2) Repeatedly merge sublists to produce new sorted sublists until there is only one sublist remaining. This will be the sorted list.
  3) Write a merge function to merge the two halves.
  4) Create the recursive merge sort function.
# Submissions 
 git push your solution in this repo and hit /submit in Discord