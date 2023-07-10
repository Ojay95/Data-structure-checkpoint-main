# Data-structure-checkpoint-main
This repository contains two algorithms: Algorithm 1 and Algorithm 2. These algorithms are briefly described below.

Algorithm 1: Palindrome Check
This algorithm checks whether a given number is a palindrome or not. It follows the steps outlined below:

Read the number to check as n.
Initialize variables s to 0 and t to n.
While n is not equal to 0, repeat the following steps:
Set r to the remainder of n divided by 10.
Update s by multiplying it by 10 and adding r.
Update n by dividing it by 10.
If n is equal to t, display that n is a palindrome. Otherwise, display that n is not a palindrome.

Algorithm 2: Insertion Sort
This algorithm performs an insertion sort on an array of items. The steps of the algorithm are as follows:

Initialize variables holePosition and valueToInsert.
Iterate over each element in the array A from index 1 to length(A) inclusive.
Select the value to be inserted and assign it to valueToInsert.
Set holePosition to i.
While holePosition is greater than 0 and the element at index holePosition-1 is greater than valueToInsert, repeat the following steps:
Shift the element at holePosition-1 to holePosition.
Decrement holePosition by 1.
Insert valueToInsert at the hole position.
Repeat steps 3-6 until the iteration is complete.
Please refer to the actual JavaScript code for a detailed implementation of each algorithm.

Note: These algorithms are provided as a reference and can be adapted or modified to suit specific requirements.

Feel free to explore the code and use these algorithms as needed!
