Tree Implementation Uing AVL: Tree is one of the most important data structure that is used for efficiently performing operations like insertion, deletion and searching of values. However, while working with a large volume of data, construction of a well-balanced tree for sorting all data s not feasible. Thus only useful data is stored as a tree, and the actual volume of data being used continually changes through the insertion of new data and deletion of existing data. You will find in some cases where the NULL link to a binary tree to special links is called as threads and hence it is possible to perform traversals, insertions, deletions without using either stack or recursion. In this chapter, you will learn about the Height balance tree which is also known as the AVL tree.

AVL tree is a binary search tree in which the difference of heights of left and right subtrees of any node is less than or equal to one. The technique of balancing the height of binary trees was developed by Adelson, Velskii, and Landi and hence given the short form as AVL tree or Balanced Binary Tree.

An AVL tree can be defined as follows:

Let T be a non-empty binary tree with TL and TR as its left and right subtrees. The tree is height balanced if:
1. TL and TR are height balanced
2. hL - hR <= 1, where hL - hR are the heights of TL and TR
3. The Balance factor of a node in a binary tree can have value 1, -1, 0, depending on whether the height of its left subtree is greater, less than or equal to the height of the right subtree.
