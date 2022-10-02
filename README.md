# Text-Editor-in-Python

# Table of contents;

Abstract ;
The Introduction
The  Methodology and functioning
 Specification and use
 Result Discussion 
 Conclusions
 
# The Abstract and main crucks;
 \
We have designed a functionality through which users can Undo or Redo there most recently performed function. We made a linked list in which any deleted element is stored on each index respectively as deleted and when undo is called the deleted elements take their places accordingly, Redo function also works in the same way.
User can also implement any data structure of their choice such as linked list, stack and queue.

\

# Steps to Create Text Editor Using Python;
Importing libraries: # Import required modules and liberaries. from tkinter import * ...
Create the main window: stimulator_window = Tk() ...
Creating the Text Area, Scrollbar and Button: scrollbar = Scrollbar(stimulator_window. ...
Save() Function: def save(): ...
Main command: # command to run.


# Introduction


We have designed a text editor in python which we will take input from user and give option to enter text as string or to read from directory, we will also giver user option to enter data by word or by character i.e in by word menu the program will store one word in one index and in by character menu the program will take each character as one index.

# Implementation of doubly link list;

We have selected number of data structures to implement text editor one of which is doubly linked user will be given options to select from number of data structures.

# Implementation of stack;

Stack will be implemented by last in first out principle where each index will represent character or word respectively. Where only latest entered element can be deleted first and elements are inserted at zero index!

# Implementation of queue;

Queue will be implemented by first in and first out principle where each index will represent character or word respectively. Where first entered element are deleted first
 Implementation of  Undo  and Redo operations:
 
For undo and redo operations we have created two separate lists where words/characters, their index, and their operation performed will be stored.
 If user enter any word or character in main list ,that  word/character , it’s index and operation will also be  stored in undo list , if user clicks undo button, then the word stored  at end of undo list  will be delete or inserted depends on the operation performed  on that word/character before.
 In short, we use stack (LIFO)for undo and redo operations.

# #Specification;

Implementation of LIFO (STACK)
Implementation of FIFO (First in First out)
Implementation of Doubly linked list
Implementation of GUI (Tkinter)
Undo and Redo functionality
Insert at Arbitrary, start or at ending positions

# The results and conclusion;

We have designed a project that covers all the basic concepts of Data Structures and Algorithms. We have implemented different structures used in Data structures such as LIFO(Stack), FIFO(Queues) and linked list. We have also designed undo and redo functionality that will enhance work capability of programmers or notepad users. This project also includes the Graphical user interface (GUI)Which was designed using a python directory known as Tkinter. We have designed buttons, text boards and boxes through which users can check full capability of the project more precisely

![uiooo](https://user-images.githubusercontent.com/92621862/193036513-7102e59e-b510-4f07-866a-9d23ef0c1845.PNG)




