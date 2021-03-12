# Advanced-Tower-of-Hanoi
Tower of Hanoi is a fun puzzle game where the goal is to move an entire stack of disks from one position (stack) to another. With the addition of a new challenge to make the transportation cost more difficult.

# Artificial Intelligence (Advanced Tower of Hanoi)

Tower of Hanoi is a fun puzzle game where the goal is to move an entire stack of disks from one position (stack) to another. Three simple rules are followed:
   
   1)  Only one disk can be moved at a time.
   2)	Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack. In other words, a disk can only be moved if it is the uppermost disk on a stack.
   3)	No larger disk may be placed on top of a smaller disk.

The main objective of this assignment is to formulate the tower of hanoi puzzle as a search problem so that a more generalized solution can be used to solve it. However, in this advanced Tower of Hanoi problem:

  ●	We might have from 3 to 6 stacks.
  
  ●	We might have from 3 to 10 disks.
  
  ●	There are 2 types of stacks.
        
      a.	Wide stacks: the cost of taking the upper disk or placing a disk on top of such stacks is 2.      
      b.	Narrow stacks: the cost of taking the upper disk or placing a disk on top of such stacks is 1.

To solve this problem you need to implement both UCS and A* algorithms to solve this advanced ToH problem.

The input to your application is: 
1)	The number of stacks
2)	The number of disks
3)	The current state
4)	The goal state
5)	Which stacks are narrow and which are wide

The output of your program should be:
1.	The list of all movements from the start state to the goal state (stored in a file each movement in a separate line)
2.	the number of nodes expanded from the fringe until the goal is reached for each algorithm
 



Consider the following while implementing your solution:

●	You are free to choose any suitable heuristic function, but you need to show that it is admissible. (Be creative)
 
●	Try to come up with more than one heuristic and compare between them with respect to the number of expanded nodes.
