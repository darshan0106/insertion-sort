# Insertion Sort Algorithm
**Introduction**

Insertion Sort is a simple and efficient comparison-based sorting algorithm. It builds the final sorted array one item at a time by repeatedly picking the next item and inserting it into its correct position among the already sorted items.

**Time Complexity**

* Best Case: O(n) - The list is already sorted.
* Average Case: O(n^2) - The list is in random order.
* Worst Case: O(n^2) - The list is in reverse order.
Here, n is the number of elements in the list.

**Code Explanation**

1 **Explanation**

**Function Definition:**

* The insertionSort function takes one parameter: arr (a list of integers to be sorted).

2 **Outer Loop:**

* The outer loop runs from i = 1 to n-1 (where n is the length of the list). This loop picks each element one by one starting from the second element.

3 **Key and Inner Loop:**

* The key variable holds the value of the current element to be inserted into the sorted part of the list.
* The inner loop runs as long as j is greater than or equal to 0 and the element at arr[j] is greater than key. It shifts elements of the sorted segment to the right to create the correct position for key.

4 **Insert Key:**

* Once the correct position for key is found, it is inserted into the sorted part of the list.

5 **Return Sorted Array:**

* After the loops complete, the sorted list arr is returned.

6 **User Input:**

*The user is prompted to enter the elements of the array as a space-separated string. This input is converted to a list of integers using map and list.

7 **Print Before Sorting:**

* The original array is printed before sorting.

8 **Function Call and Result:**

* The insertionSort function is called with the user-provided array.
* The sorted array is printed to the console.

**Usage**
* Run the code.
* Enter the elements of the array when prompted. Separate each element with a space.
* The program will output the original array before sorting and the sorted array after applying insertion sort.
