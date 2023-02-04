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

## Binary Tree & Binary Search Tree  
- Balanced binary tree
- Complete binary tree
- Binary search tree

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

## Graph Search Algorithm   
### Breadth-first search (BFS-1)
Determine whether a binary tree is a complete binary tree
### Best first search (BFS-2)
Dijkstra’s Algorithm 
### Depth-first search (DFS)
1. print all subsets of a set
2. print all valid permutations of () () ()

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
