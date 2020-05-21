## What is a Linked List?
- A Linked List is a sequence of Nodes that are connected/linked to each other. 
- Linked List - A data structure that contains nodes that links/points to the next node in the list.

## Traversal
- When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing.
- The best way to approach a traversal is through the use of a while() loop.

## Big O
- The Big O of time for Includes would be O(n). This is because, at its worse case, the node we are looking for will be the very last node in the linked list.
- The Big O of space for Includes would be O(1). This is because there is no additional space being used than what is already given to us with the linked list input.

## Prerequisites
- When making your Node class, consider requiring a value to be passed in to require that each node has a value.
- When making a Linked List, you may want to require that at least one node gets passed in upon instantiation.

## Advantages of a linked list
- In contrast to an array which stores data contiguously in memmory a linked list can easily insert or remove nodes from the list without reorganization of the entire data structure.
