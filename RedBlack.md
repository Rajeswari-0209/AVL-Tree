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
 <p>After every insertion operation, we need to check all the properties of Red-Black Tree. If all the properties are satisfied then we go to next operation otherwise we perform the following operation to make it Red Black Tree.</p>

1. Recolor
2. Rotation
3. Rotation followed by Recolor

