# Denomination-Problem


Problem Description

Given a value V we want to make a change for V Rs. The objective of the problem is to make the change of V Rs in the least number of denominations.

Problem Formulation

We have an infinite supply of each of the denominations in Indian currency, i.e., we have an infinite supply of {1, 2, 5, 10, 20, 50, 100, 500, 1000} valued coins/notes. The way this problem is solved is to start from the largest possible denomination and keep adding denominations while the remaining value is greater than 0. 

Algorithm

1.	Sort the array of coins in decreasing order.
2.	Initialize result as empty.
3.	Find the largest denomination that is smaller than current amount.
4.	Add found denomination to result. Subtract value of found denomination from amount.
5.	If amount becomes 0, then print result.
6.	Else repeat steps 3 and 4 for new value of V.
