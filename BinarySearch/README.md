
# Binary Search

Binary Search is a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(Log n). 



## Binary Search Algorithm:

- Begin with the mid element of the whole array as a search key.

- If the value of the search key is equal to the item then return an index of the search key.

- If the value of the search key is less than the item in the middle of the interval, narrow the interval to the lower half.
- Otherwise, narrow it to the upper half.
- Repeatedly check from the second point until the value is found or the interval is empty.



## Binary search vs sequential search

![binary search vs sequential search](https://media.tenor.com/Jl0YrqxnHmAAAAAd/binary-search-sequence-search.gif)

 locate item in 3 steps instead 37 steps