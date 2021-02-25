# AVL-Tree(AVL Stands for Adelson-Velsky and Landis)

- AVL tree is a **height-balanced binary search tree**.
- A binary tree is said to be balanced if, the difference between the heights of left and right subtrees of every node in the tree is either **-1, 0 or +1**. 
- In an AVL tree, every node maintains an extra information known as balance factor. 
<p>
              <h3>Balance factor = heightOfLeftSubtree - heightOfRightSubtree </h3> </p>
               
Example of AVL Tree

![AVL Tree](https://github.com/Rajeswari-0209/AVL-Tree/blob/main/AVL-Tree.png)

The above tree is a binary search tree and every node is satisfying balance factor condition. So this tree is said to be an AVL tree.
**AVL Tree Rotations**
- In AVL tree, after performing operations like insertion and deletion we need to check the balance factor of every node in the tree.
- If every node satisfies the balance factor condition then we conclude the operation otherwise we must make it balanced. 
- Rotation operations are used to make the tree balanced.
<p>There are four rotations and they are classified into two types.</p>

* Single Rotation
  * Left Rotation (LL Rotation)
  * Right Rotation (RR Rotation)
* Double Rotation
  * Left Right Rotation (LR Rotation)
  * Right Left Rotation (RL Rotation)
<p>
Left Rotation:
  -In LL Rotation, every node moves one position to left from the current position. 
  </p>
  
  ![AVL Tree](https://github.com/Rajeswari-0209/AVL-Tree/blob/main/LL-Rotation.png)
 
  <p>
Right Rotation:
 -In RR Rotation, every node moves one position to right from the current position.
</p>

 ![AVL Tree](https://github.com/Rajeswari-0209/AVL-Tree/blob/main/RR-Rotation.png)
 
 <p>
Left Right Rotation:
 -In LR Rotation, at first, every node moves one position to the left and one position to right from the current position.
</p>

![AVL Tree](https://github.com/Rajeswari-0209/AVL-Tree/blob/main/LR-Rotation.png)

 <p>
Right Left Rotation:
 -In RL Rotation, at first every node moves one position to right and one position to left from the current position. 
</p>

![AVL Tree](https://github.com/Rajeswari-0209/AVL-Tree/blob/main/RL-Rotation.png)

<p> Operations on an AVL Tree </p>

<p>The following operations are performed on AVL tree 
</p>
  <p>1.Search
</p>
   <p>2.Insertion
</p>
   <p>3.Deletion
</p>

<h3> Search Operation in AVL Tree </h3>
<p>
-In an AVL tree, the search operation is performed with O(log n) time complexity. 
  </p>
  <p>
-The search operation in the AVL tree is similar to the search operation in a Binary search tree. 

</p>

<h3>Insertion Operation in AVL Tree </h3>
<p> - In an AVL tree, the insertion operation is performed with O(log n) time complexity. </p>
<p> -In AVL Tree, a new node is always inserted as a leaf node. </p>
The insertion operation is performed as follows...

<p>Step 1 - Insert the new element into the tree using Binary Search Tree insertion logic.</p>
<p>Step 2 - After insertion, check the Balance Factor of every node.</p>
<p>Step 3 - If the Balance Factor of every node is 0 or 1 or -1 then go for next operation.</p>
<p>Step 4 - If the Balance Factor of any node is other than 0 or 1 or -1 then that tree is said to be imbalanced. In this case, perform suitable Rotation to make it balanced and go for next operation.</p>
<h3>Deletion Operation in AVL Tree</h3>
<p>The deletion operation in AVL Tree is similar to deletion operation in BST. But after every deletion operation, we need to check with the Balance Factor condition. If the tree is balanced after deletion go for next operation otherwise perform suitable rotation to make the tree Balanced.</p>
              

