# LinkedList2
Recall the algorithm for Selection Sort:  
Step 1) Find the min value in the unsorted subset  
Step 2) Move that value into the 1st location of the unsorted subset  
Repeat these 2 steps n-1 times (where n is the size of the original set of unsorted values)  
<br />
For this assignment, you will create a program that will perform this algorithm on an unsorted LinkedList2 object.  
LinkedList2 is the class that used Node2 objects that had pointers to go both to next and previous.   
(***HINT*** In order to generate an unsorted list for your own testing purposes, use the append method instead of the insert method.)  
Create methods "move" and "findMin" in class LinkedList2 according to the requirements listed below.   
Create a main method in class Homework4 according to the requirements listed below.  
a)	Create a method called "findMin" that will start searching the list from the node passed as a parameter until the end of the list.  
DO NOT search the list from the head node.  
The method should return the node with the smallest int value.  
DO NOT return the int.  
<br/>
<br/>
b) Create a method called "move" that will take in 2 node objects as parameters.  
You may assume that the 2 nodes both exist in the same list and you may assume that the 2 parameters are not pointing to the same node.  
The method should remove the node of the first parameter from its current location in the list and then re-insert it into the list immediately before the node of the second parameter.  
c) Create a main method that repeatedly (n-1 times) calls method findMin and then take the node returned from that method and by using method move, moves the node returned from findMin before the 1st location of the unsorted part of the list,  
(**NOTE** this is not swapping values like we did with arrays, it is behaving slightly differently).  
BEFORE calling method move, check to see if the node returned from the findMin method is already in the first location of the unsorted portion of the list. If it is, DO NOT call method move.  

