# Assignment-1
Assignment 1 for TCSS

The purpose of this assignment is to set up the programming environment and to implement sorting code snippets from websites into an insertion sorting program.

sort 1: found at: https://gist.github.com/mycodeschool/9678029

sort1 is a merge sort, the most efficient and quickest of the sorting algorithms. Its purpose is to "divide and conquer" an array by sorting the smallest amount of items (1:1) then sorting that group with more groups then finally between two main groups. This sorting algorithm's average performance is O(nlogn) which makes it an efficient algorithm.

sort2: found at: http://quiz.geeksforgeeks.org/bubble-sort/ (under C/C++)

sort2 is a bubble sort which is a very slow and inefficient sorting algorithm that only compares two items in an array then swaps them. This algorithm is slow as it runs through the array as many times as it can until it is sorted, meaning that once two items in the array is sorted it will move forward by 1 index and swap; once the sort reaches the end of the array it starts over and continues to compare items within each index until the sort is complete. This algorithm's average performance is O(n^2) which makes it more inefficient than the merge sort as depicted from the times that were displayed when the sorting was finished:

Insertion sort took 11296 ms
sort1 took 30 ms
sort2 took 55954 ms

