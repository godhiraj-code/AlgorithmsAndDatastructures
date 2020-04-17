# AlgorithmsAndDatastructures 
Algorithms and Data Structures in go - Problems set are from [leetcode.com](https://leetcode.com/problemset/all/) 

The Problems set are being taken from [leetcode](https://leetcode.com/problemset/all/) . 


1. [Maximum consecutive 1's in an array of zeros and ones .](https://play.golang.org/p/KtNr9XS6aOT) 

-- Given an array of 1's and 0's , We need to find the maximum consecutive's 1 that can be in that array. 

**My approach** :  
  a) range over that array and check the value , if value is zero , then assign a counter variable to zero 
  otherwise , increment the counter variable
  b) then pass that incremented counter variable into a function that will find the no of max consecutive 1 
  
  
2. [Find Numbers with Even Number of Digits](https://play.golang.org/p/KP1Mt-LxcGc) 

-- Given an array nums of integers, return how many of them contain an even number of digits. 
 
**My approach** : 
  just divide the number iteratively by 10 to find the no of digits and return it . (need to do it in more efficient way), will come back later. 
  

3. [Find squares of a sorted Array](https://play.golang.org/p/M-jWgNXpW7w)

--Given an array of integers A sorted in non-decreasing order, return an array of the squares of each number, also in sorted non-decreasing order.

**My approach** :
First I range over the array to find the squares and then sorted that array by looping over the slice and comparing the element and then swapping the element in ascending order of their value 
