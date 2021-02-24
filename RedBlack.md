# Red - Black Tree 

- Red Black Tree is a Binary Search Tree in which every node is colored either **RED or BLACK**.
- In Red Black Tree, the color of a node is decided based on the properties of Red-Black Tree. 
<h3>Properties of Red Black Tree</h3>
<p>
Property 1: Red - Black Tree must be a Binary Search Tree.
  </p>
<p>  
Property 2: The ROOT node must be colored BLACK.
</p>
<p>
Property 3: The children of Red colored node must be colored BLACK. (There should not be two consecutive RED nodes).
  </p>
  <p>
Property 4: In all the paths of the tree, there should be same number of BLACK colored nodes.
  </p>
  <p>
Property 5: Every new node must be inserted with RED color.
  </p>
  <p>
Property 6: Every leaf (e.i. NULL node) must be colored BLACK.
  </p>
  Example of Red-Black Tree
  
  ![Red-Black Tree](https://github.com/Rajeswari-0209/AVL-Tree/blob/main/Red-BlackTree.png)
  <p>
  The above tree is a Red-Black tree where every node is satisfying all the properties of Red-Black Tree.</p>
  
  <h3>Insertion into RED BLACK Tree</h3>
  <p>-In a Red-Black Tree, every new node must be inserted with the color RED.</p>
 <p>-The insertion operation in Red Black Tree is similar to insertion operation in Binary Search Tree. But it is inserted with a color property.</p>
 <p>-After every insertion operation, we need to check all the properties of Red-Black Tree. If all the properties are satisfied then we go to next operation otherwise we perform the following operation to make it Red Black Tree.</p>

1. Recolor
2. Rotation
3. Rotation followed by Recolor
<p>
The insertion operation in Red Black tree is performed using the following steps...</p>
<p>
Step 1 - Check whether tree is Empty.</p>
<p>
Step 2 - If tree is Empty then insert the newNode as Root node with color Black and exit from the operation.</p>
<p>Step 3 - If tree is not Empty then insert the newNode as leaf node with color Red.</p>
<p>Step 4 - If the parent of newNode is Black then exit from the operation.</p>
<p>Step 5 - If the parent of newNode is Red then check the color of parentnode's sibling of newNode.</p>
<p>Step 6 - If it is colored Black or NULL then make suitable Rotation and Recolor it.</p>
<p>Step 7 - If it is colored Red then perform Recolor. Repeat the same until tree becomes Red Black Tree.</p>

