# EvensemLab2Juet



Exercises:
1. Write a function that will return the length of a character string using pointer. You are
not allowed to use the strlen C library function.
2. Write a function that finds the minimum and the maximum value in an array of N integers. Inputs to the function are the array of integers, an integer variable containing the length of the array and pointers to integer variables that will contain the minimum and the maximum values. The function prototype is:
void minmax( int array[], int length, int * min, int * max);
Write a main function that uses this function to find and display the minimum and the maximum values of an array of integers.
3. Write a menu driven program (using switch-case) to create a database of student names and perform the following operations using array of character pointers and dynamic memory allocation.
(A)To insert a student name
(B) To delete a name (Show Error message if zero names are there in database) (C)To print the names
Note: your program should keep on showing above three options until user enters ‘N’.
4. Write a program to generate random numbers in given range [m, n]. Test case :
Input: m=10, n=50 Output: 34
 
5. An automobile company has serial number for engine parts starting from AA0 to FF9. The other characteristics of parts to be specified in a structure are: Year of manufacturing, material (Steel, Aluminum, Iron etc.) and quantity manufactured.
Write a program to include following tasks:
(a) Specify a C structure that includes four members viz. serial numbers, year of manufacturing, material type, and quantity. Declare an array of structure of size 60.
(b) Automatically initialize the values of structure members as follows :
i. Generate serial numbers such that first part has serial number AA0 and 60th part has serial number FF9.
ii. Randomly generate year of manufacturing in the range [1990-2018]
iii.Randomly initialize material type from three choices ie. Steel, Aluminum, Iron
iv.Randomly initialize quantity in the range [1-1000]
(c) Display the information of the parts with serial numbers between any given range such as [BB1,CC6].
Advance practice problems
1. Given an array A of size N-1 and given that there are numbers from 1 to N with one element missing; Write program to find the missing number.
Test case 1: Given array: 1 2 3 5; missing element is 4.
Test case 2: Given array: 1 2 3 4 5 6 7 8 10; missing element is 9.
