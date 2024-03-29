## Radix Sort

##### The radixSort function is the implementation of the Radix Sort algorithm. It starts by finding the maximum number of digits in the given array using mostDigits. Then, for each digit position from the least significant to the most significant, it creates 10 empty buckets corresponding to the possible digits (0 to 9). It places each number in the array into the appropriate bucket based on the current digit. After processing all digits, the numbers are collected back from the buckets in their new order. This process is repeated for all digits, and the final sorted array is returned.

##### Radix Sort has a time complexity of O(nk), where n is the number of elements in the array and k is the number of digits in the longest number. It is a stable sorting algorithm, meaning that the relative order of equal elements is preserved in the sorted output.
##### ClickHere:- https://ramya-brs.github.io/Radix-Sort/