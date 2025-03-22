# second-and--thirid-largest-integer
## Student Information
- **Name**: Lealem Sisay
- **Student ID**: RNS-0262/23
- **Course**: DSA
## Algorithm
Algorithm for finding the second largest integer in an array:

Input: An array 'arr' of integers and its size 'size'.

Output: The second largest integer in the array, or -1 if the array has less than 2 elements.

1.  If 'size' is less than 2, return -1.
2.  Initialize 'first' to 'arr[0]' and 'second' to -1.
3.  Iterate through the array from index 1 to 'size' - 1:
4.  If 'arr[i]' is greater than 'first':
5.  Set 'second' to 'first'.
6.  Set 'first' to 'arr[i]'.
7.  Else if 'arr[i]' is greater than 'second' and 'arr[i]' is not equal to 'first':
8.  Set 'second' to 'arr[i]'.
9.  Return 'second'.

Algorithm for finding the third largest integer in an array:

Input: An array 'arr' of integers and its size 'size'.

Output: The third largest integer in the array, or -1 if the array has less than 3 elements.

1.  If 'size' is less than 3, return -1.
2.  Initialize 'first' to 'arr[0]', 'second' to -1, and 'third' to -1.
3.  Iterate through the array from index 1 to 'size' - 1:
4.  If 'arr[i]' is greater than 'first':
5.  Set 'third' to 'second'.
6.  Set 'second' to 'first'.
7.  Set 'first' to 'arr[i]'.
8.  Else if 'arr[i]' is greater than 'second' and 'arr[i]' is not equal to 'first':
9.  Set 'third' to 'second'.
0. Set 'second' to 'arr[i]'.
11. Else if 'arr[i]' is greater than 'third' and 'arr[i]' is not equal to 'second' and 'arr[i]' is not equal to 'first':
12. Set 'third' to 'arr[i]'.
13. Return 'third'.

How to Run the C++ Code:

1.  Save the provided C++ code to a file, for example, `largest_numbers.cpp`.
2.  Open a terminal or command prompt.
3.  Navigate to the directory where you saved the file.
4.  Compile the code using a C++ compiler (like g++):
    ```bash
    g++ largest_numbers.cpp -o largest_numbers
    ```
5.  Run the executable:
    ```bash
    ./largest_numbers
    ```
    This will execute the program and print the second and third largest numbers in the array.