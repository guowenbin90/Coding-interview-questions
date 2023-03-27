# Coding-interview-questions
https://www.algoexpert.io/questions  
https://leetcode.com/problemset/all/

## Steps
1. Document your assumptions
2. Explain your approach
3. Provide code comments
4. Explain the big-O
5. Identify any additional data structures
6. Only provide your best answer

- Selection Sort
- Quick sort
- Merge sort
- Call stack
## Binary search 
(can be used to find the closest number)

## Queue, Stack and LinkedList  
Queue: FIFO = First in first out  
Stack: LIFO = Last in first out  
push{}, pop{}, top{}

LinkedList key points:
- When you want to de-reference a ListNode, make sure it is not a NULL pointer
- Never ever lost the control of the head pointer of the LinkedList

## Binary Tree & Binary Search Tree  
Applications: social networks analysis, information indexing

- Balanced binary tree
- Complete binary tree
- Binary search tree

1. Get Height of a binary tree
2. Determine whether a binary tree is a balanced binary tree
3. Judge whether a binary tree is symmetric
4. Determine whether two binary trees’ structures are identical

## Heap Search Algorithm  

Heap Property:  
- every element of the tree is larger than any of its descendants if they exists.
- complete binary tree
- Max Heap, Min Heap
- Index of lchild= index of parent X*2 +1
- Index of rchild= index of parent X*2 +2
- Unsorted but follow rules above  

Heap operation:
- insert: O(logn)
- update: O(logn)
- get/top: O(1)
- pop: O(logn)
- heapify: unsorted array to Heap, O(n)

1. Find smallest k elements from an unsorted array of size n

## Graph Search Algorithm   
### Breadth-first search (BFS-1)
Determine whether a binary tree is a complete binary tree
### Best first search (BFS-2)
Dijkstra’s Algorithm  
Usages: Find the shortest path cost from a single node (source node) to any other nodes in that graph  
Example problem: Find the shortest distance among cities  
Data structure: priority_queue (Min_heap)
### Depth-first search (DFS)
1. print all subsets of a set
2. print all valid permutations of () () ()

Basic solution:
- What does it store on each level?
- How many different states should we try to put on this level?
## Hash Table
- Hash set <key1, key2>
- Hash map <key, value>

## String
1. Removal  
    1.1 remove some particular chars from a string  
	  1.2 remove all leading/trailing/duplicated empty spaces from a string
2. De-duplication     aaaaabbbbb_ccc → ab_c
3. Replace empty space  “ “ with “20%”
4. Reversal (swap)  
5. Substring finding  
6. Move letters around e.g. ABCD1234 → A1B2C3D4
7. Permutation (use DFS)
8. Decoding encoding   aaaabcc → a4b1c2
9. Longest substring that contains only unique chars
10. Matching (*.?)
## Bit Representation
- Unsigned int 64 bits	2^64 -1  
- Int 32bits		2^32 -1
- & AND vs if(true1 && true2)
- | OR  vs if(true1 || true2) 
- ~ NOT
- ^ XOR 
- "<<" left shift: add 0 on the right side
- ">>" right shift: add 0 on the left side

1. determine whether a number x is a power of 2 (x==2^n)  n>0
