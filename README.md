# DSA_Problems_BST

Insert a node in a BST
You are given the root node of a binary search tree (BST) and a value key to insert into the tree.

Return the root node of the BST after the insertion.

Note : There is no duplicate values present in the BST.

Note : It is guaranteed that the new value does not exist in the original BST.

Input Format
The first line contains an integer N , represents total number of nodes in BST.

Second line contains N integers , representing Nodes of BST.

Third line contains an integer key which needs to be inserted into the BST tree.

Output Format
Print the Preorder traversal of the BST in a new line.

Example 1
Input

6
2 81 87 90 42 41 
44

Output


2 81 42 41 44 87 90 

Explaination

     2
      \
       81
      /  \
     42   87
     /  \   \
    41  44   90 
    

As 44 is not present in the given nodes, so the tree will change and preorder of the updated tree is 2 81 42 41 66 44 87 90. 

Example 2
Input

3
14 3 11 
8

Output


14 3 11 8 

Explaination

     14
    / 
   3
    \ 
     11  
    /
    8  

preorder of the updated tree is 14 3 11 8.

Constraints:
1 <= N <= 10^4

1 <= Node.val, Key <= 10^5