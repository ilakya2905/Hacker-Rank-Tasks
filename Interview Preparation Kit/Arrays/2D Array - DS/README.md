# 2D Array - DS in C
Given a  2D Array, :

1 1 1 0 0 0__
0 1 0 0 0 0__
1 1 1 0 0 0__
0 0 0 0 0 0__
0 0 0 0 0 0__
0 0 0 0 0 0__
An hourglass in  is a subset of values with indices falling in this pattern in 's graphical representation:

a b c__
  d__
e f g__
There are  hourglasses in . An hourglass sum is the sum of an hourglass' values. Calculate the hourglass sum for every hourglass in , then print the maximum hourglass sum. The array will always be .

Example


-9 -9 -9  1 1 1__ 
 0 -9  0  4 3 2__
-9 -9 -9  1 2 3__
 0  0  8  6 6 0__
 0  0  0 -2 0 0__
 0  0  1  2 4 0__
The  hourglass sums are:__

-63, -34, -9, 12,__
-10,   0, 28, 23,__
-27, -11, -2, 10,__
  9,  17, 25, 18__
The highest hourglass sum is  from the hourglass beginning at row , column :__

0 4 3__
  1__
8 6 6__
Note: If you have already solved the Java domain's Java 2D Array challenge, you may wish to skip this challenge.

Function Description

Complete the function hourglassSum in the editor below.

hourglassSum has the following parameter(s):

int arr[6][6]: an array of integers
Returns

int: the maximum hourglass sum
Input Format

Each of the  lines of inputs  contains  space-separated integers .

Constraints

Output Format

Print the largest (maximum) hourglass sum found in .


Sample Output

19
