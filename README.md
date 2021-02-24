# AVL-Tree

- AVL tree is a **height-balanced binary search tree**.
- A binary tree is said to be balanced if, the difference between the heights of left and right subtrees of every node in the tree is either **-1, 0 or +1**. 
- In an AVL tree, every node maintains an extra information known as balance factor. 
              **Balance factor = heightOfLeftSubtree - heightOfRightSubtree**
               
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

<p>The following operations are performed on AVL tree </p>
   * Search
   * Insertion
   * Deletion
              

