[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Am2hlQFs)
# Who Gets the Cake (Part 2)

Learning Goals 
==============

* Insert and delete nodes in a linked list 

Changes from HW01 Cake
=====================

In HW01 Cake, an array is used to keep track who is still in the
game. In this assignment, a linked list is used.  The output of your
program should match the output of HW01 Cake. In addition, the linked
list is printed every time one number is removed.

The files in `expected` directory have `-DDEBUG` in `Makefile` to turn
on the code printing the lists starting from the nodes to be
eliminated.  If `Makefile` does not have `-DDEBUG`, the outputs should
be the same as the files in HW01 Cake.

Initialize Pointers
===================

You should *always* initialize pointers to NULL.  Uninitialized
pointers can make your programs' behavior unpredictable. 

Printing ListNode
===================

You should call `printListNode` each time BEFORE you delete any node 
and print the node value. In the expected files, `printListNode` is not
called for the last value in the list. Follow the 
expected files format. You can turn on the DEBUG flag in your Makefile
for printing.

Helpful Notes
==========================
For this assignment, it will be beneficial to first complete `createList` 
and `deleteNode` functions before trying to complete `eliminate`, as 
these are important building blocks for the `eliminate` function, 
which is the most complicated piece of this assignment. While working on `createList` 
and `deleteNode`, you are encouraged to write your own test cases to ensure your code is working as expected.

Submitting
==========================
For this assignment, you only need to submit your `hw10.c` file. Zipping it in a folder is optional.