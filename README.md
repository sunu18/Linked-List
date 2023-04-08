# Linked-List
n C programming language, a linked list is a data structure that consists of a sequence of nodes, where each node contains a value and a pointer to the next node in the list. Linked lists are useful when you need to store and manipulate data that can grow or shrink dynamically during the execution of your program. Here is an example of how to define a linked list in C:

![image](https://user-images.githubusercontent.com/91204160/230720341-ef6cd330-7744-431d-98d0-b14d93b7eaa5.png)

In this example, we have defined a structure named Node that contains two member variables: data (an integer value) and next (a pointer to the next node in the list).

To create a linked list, you need to create a series of nodes and link them together using pointers. Here is an example of how to create a linked list with three nodes:

![image](https://user-images.githubusercontent.com/91204160/230720361-4f83af25-f4c9-4aa2-a679-c9afedc8ac9d.png)

In this example, we have created three nodes using dynamic memory allocation and assigned values to their data member variables. We have also linked the nodes together using the next pointers.

To traverse the linked list and access the values stored in each node, you can use a loop that starts at the head of the list and follows the next pointers until it reaches the end of the list (where next is NULL). Here is an example of how to print the values of each node in the list:

![image](https://user-images.githubusercontent.com/91204160/230720383-90234d8b-a22c-43f0-b7de-65c52b293f26.png)

In this example, we have used a while loop to traverse the linked list starting from the head node. We have printed the data value of each node and updated the current pointer to point to the next node in the list.

Linked lists are a powerful data structure in C and can be used to implement various algorithms and data structures, such as stacks, queues, and hash tables. However, they can also be complex to work with and require careful memory management to avoid memory leaks and other issues.
