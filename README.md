# Problem Statements

## Week 4 Day 1

- Given an array of string, write a function using **spread syntax** that creates a new array using the given array and adds one string at the start and the other at the end.
For example for a given input [‘Javascript’, ‘Python’, ’Scala’], your function should create a new array - [’Start’, ‘Javascript’, ‘Python’, ’Scala’, ‘End’]. 
**Note:** Don’t iterate over the given array, use spread syntax.
- Given 2 separate arrays of numbers or strings. Write a function using the **spread syntax** that creates 2 new arrays merging the two given arrays in both the possible orders. ﻿
For example, 
Given [1, 2, 3] and [4, 5, 6]. The 2 new arrays created should be [1, 2, 3, 4, 5, 6] and [4, 5, 6, 1, 2, 3]
Or given [‘January', ‘February’, ‘March’] and [‘April’, ‘May’, ‘June’]. The 2 new arrays created should be [‘January', ‘February’, ‘March’, ‘April’, ‘May’, ‘June’] and [‘April’, ‘May’, ‘June’, 'January', ‘February’, ‘March’ ]
- Write a function using the **rest syntax** that can take any number of parameters as input and returns the sum of all the provided numbers.
For example. Your function should work for inputs 1,2 as well as 1,2,3 and 1,2,3,4,5
- Given an array, using **destructured assignment** declare variables and assign values to them in a single statement. For logging them on console you can use multiple statements. For example, for a given array [250, 321, 1000, 209], create variables having values 250, 321, 1000 and 209 in a single statement without iterating through the array.
- Using the same assignment method ang given an array of values, declare 3 variables and also assign values to them within a single statement such that the first variable has the first element of the given array as its value, the second variable has the second element of the given array as its value and the third variable is an array containing the rest of the values of the array. The input array can contain any number of elements. You can assume the input array will always have atleast 3 elements.
For example, if the given array is [1, 2, 3, 4, 5] and you declare variables a, b and c then a should have a value 1, b should have a value 2 and c should have a value [3, 4, 5]
