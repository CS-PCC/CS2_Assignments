# 07_03_frequency

- Accept [07_03_frequency](https://classroom.github.com/a/bbyAo7iM)
- Get [main.cpp](main.cpp)
- Get [frequency.h](frequency.h)


## Description

Create a `frequency.h` header file to write a program that reads a list of integers into an array. You may assume that there are fewer than 100 entries in the array.

The output is to be a two-column list. The first column is the count of the number of occurrences of each element, the second column is a list of the distinct array of elements. The list should be sorted into entries in the first column, largest to smallest. 

**Do NOT sort the original array before you get the frequency table! You can sort the frequency table.**


## Functions

You need initialize pass-by-ref variables (num_used and unique_num) before you use them.


### Function frequency
You need to modify original array, so do not create a new array to hold items, you can use array c[] to hold counts of items. After call frequency function, first `unique_num` of array a will contain the unique numbers.

For example,

```c++
int a = [1, 1, 7, 5, 5, 2, 1, 5];
int c = [100];
int num_used = 8;
int unique_num = 0;

// call frequency function
frequency(a, c, num_used, unique_num);

// Expected:
// unique_num = 4
// a = [1, 7, 5, 2, 5, 2, 1, 5]
// c = [3, 1, 3, 1]
```