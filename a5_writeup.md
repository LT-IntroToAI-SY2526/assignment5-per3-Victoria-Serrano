# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them?
There are lots of concepts that I have learned through this assignment. I have learned the differences betwen BFS and DFS and when is he proper way to use both of them when necessary. I learned that while backtracking, it is more beneficial to use DFS rather then BFS because it is a quicker way to develop. I learned that BFS is used for many problems including real-world problems, BFS is a benficial technique to understanding more concepts and creating new soltuions to different problems. I learned that DFS is also beneficial and used in real-world problems that occur. DFS is used as well for finding a solution to problems. Instead of working through many solutions that are able to fix problems, DFS focuses on one specific solution which can be applied to different problems. In class, while working on the functions which involve DSF and BSF, there were a couple obstacles that I had to overcome. At first, I did not know how to apply the algorithms to the different problems that were being represented in the assignment. I also did not know the codes to the functions to fix the occuring problems. To overcome these problems, I payed attention in class to understand why we were doing these specific codes and functions. I also used AI like Chatgpt for help on understanding the algorithms and which one would overall be more beneficial.


2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems?
In class, I have learned many concepts that have contributed to more benefits in solving problems in future assignments and projects. I have learned which between BFS and DFS would be better in which situation I need help with. There are many types of real-world problems which involve searching through possibilities and making decisions that are useful to use BFS and DFS such as making recipes, solving puzzles (just like Sudoku puzzles), and creating/fixing problems in different softwares. Other constraint problems that might be faced in the real-world are problems involving design and layouts such as when making housing plans, paint color, and room layout involving furniture. There are many more constraint problems in the real world where BFS and DFS must be used which can involve problems involving the different types of softwares, assigning and scheduling different assignments to the different people.



3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search?
Stacks and Queues are both completely different functions that are both very often used, but for different reasons. A stack is used as a LIFO (last in first out) type of function while a Queue is used as a FIFO (first in first out) type of function. A stack is used when the process of DFS is used. A stack is used because it allows for backtracking to be used and for a function to be used appropriately (allows for solutions to problems to be explored as deep as can be). A queue is used when the process of BFS is used. A queue is a general concept of first one in the function, is the first one to be used. A queue allows for different solutions to be explored breathly which is why there are different operations involving queues. The LIFO can be thought of as when making pancakes, the last one to be placed in a stack is often the first one to be taken out. The FIFO can be thought of as a line, and the first person in the line gets served first since they are first in line. So, LIFOs and  FIFOs are very different. Using a stack requires less memory but goes deep into solution ovr a problem. A queue goes more breath on lots of different solutions to a problem but reuires more memory to be used. Using a stack or queue can impact the search alogrithm which is being used because one requires for multiple solutions to fix a problem while another requires one specific deep understanding on a path of a solution to fix a problem.