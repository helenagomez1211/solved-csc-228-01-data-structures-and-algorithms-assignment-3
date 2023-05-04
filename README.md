Download Link: https://assignmentchef.com/product/solved-csc-228-01-data-structures-and-algorithms-assignment-3
<br>
<strong><u>Assignment 3 (Programming)</u>: Design and Implementation of a Θ(n) Algorithm to Delete all the Occurrences of an Element in a List ADT </strong>

<strong> </strong>In this programming assignment, you will design and implement algorithms to delete all the occurrences of an element (integer data) in a List ADT: implemented using a dynamic array as well as using a singly linked list.




You are given the code for both dynamic array and the singly linked list-based implementations of a List ADT. The main function in these two programs are already setup to generate random integers and fill up the contents of the list. The deleteALL(int deleteData) function is called on the list to delete all the occurrences of the ‘deleteData’ in the list.




Your task is to implement the deleteALL(…) function in both the dynamic array and singly linked listbased implementations of the List ADT. <u>Your algorithms/implementations should run in Θ(n) time</u>, where <em>n </em>is the number of elements in the list before the deletions.




The main function is written in such a way that it will print the contents of the list before and after the deletions.




<strong>Testing Procedure: </strong>

You would test your code by entering 15 as the list size and 5 as the maximum value for any element. The list will be then filled with random integers in the range [1…5]. As there are going to be 15 integers in the list, it will be definitely the case that there will be more than one occurrence for one or more integers in the list. Enter one of such integers as the input for the ‘deleteData’ and the deleteALL(…) function is called with the deleteData to delete all the occurrences of deleteData in the list.