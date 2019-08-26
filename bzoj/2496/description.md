
# Description

<div class="content"><p><span style="font-size: medium"><br/>
  Prof. Z thinks his homework is very hard for most of his students to solve (do you remember the task “Boring Homework”?) To his surprise, many students hand in correct solutions. He thinks the reason is actually the small size of the data set he used to test students’ programs rather than the low difficulty of the homework task. He decides to give his students the same homework again, but with enormous test cases. Of course, his students think his homework becomes even more boring this time. They need your help again.<br/>
  For the ones who don’t know what homework Prof. Z. had given to his students last time:<br/>
  <br/>
  You’re asked to draw a graph of a binary search tree (BST). <br/>
<i><br/>
  A binary search tree, which may sometimes also be called ordered or sorted binary tree, is a node-based binary tree data structure which has the following properties:<br/>
  The left subtree of a node contains only nodes with keys less than the node&#39;s key.<br/>
  The right subtree of a node contains only nodes with keys greater than the node&#39;s key.<br/>
  Both the left and right subtrees must also be binary search trees.<br/>
  --from Wikipedia<br/>
</i><br/>
  Given a list of integer keys that should be inserted into the BST one by one orderly, we can form a unique BST. Moreover, Prof. Z wants the students to draw the graph of this BST.<br/>
  <br/>
  The rules to draw a graph of a BST are listed below:<br/>
  <br/>
1. The graph of a 1-node BST is a single &#39;o&#39; (15th small Latin letter).<br/>
2. If a BST has a non-empty subtree, draw a single &#39;|&#39; just above the subtree&#39;s root, and a single &#39;+&#39; just above the previous drawn &#39;|&#39;. Finally, in the row of &#39;+&#39;, use the least number (including 0) of &#39;-&#39;s to connect &#39;+&#39; (corresponding to the left or right subtree) and &#39;o&#39; (denoting the parent node of the subtrees).<br/>
3. The left subtree (if exists) must be drawn on the left side of its parent. Similarly, the right subtree (if exists) must be drawn on the right side of its parent.<br/>
4. The column of the BST&#39;s root must not contain any characters belonging to left or right subtree.<br/>
5. For each node of the BST, the graph of its left subtree and the graph of its right subtree do not share common columns in the picture of the whole tree.<br/>
<br/>
  After the whole BST has been drawn, we number the rows from top to bottom, counting from 1, and so do the columns from left to right, counting from 1.<br/>
  Due to the large scale of the tree, the graph will become so large that it is impossible for Prof. Z to check every detail of the graph this time. So you are only asked to hand in m fragments of that graph to Prof. Z instead of the whole one.</span></p>
<div class="panel_bottom"><span style="font-size: medium"> </span></div>
<p><span style="font-size: medium">根据输入构造一棵二叉树，将二叉树转化为图形，并根据询问输出该图形的局部<br/>
<br/>
</span></p></div>

# Input

<div class="content"><div class="panel_content"><span style="font-size: medium">  The first line contains T, the number of test cases. T test cases follow.<br/>
  For each test case:<br/>
  The first line contains a positive integer N (N &lt;= 100000).<br/>
  The second line contains N distinct integers, each of which can be represented by a 32-bit signed integer. These numbers should be inserted into an empty BST one by one in the given order.<br/>
  The third line contains an integer M (M &lt;= 5).<br/>
  M lines follow, each contains four integers, which are the row and column number of the top left corner, and the number of rows Ri and columns Ci of the required graph fragment, respectively. All the input integers will be positive and fit into a 32-bit signed integer, except Ri and Ci, which will be less than or equal to 200 and greater than 0.<br/>
</span></div></div>

# Output

<div class="content"><div class="panel_content"><span style="font-size: medium">For each test case:<br/>
<br/>
  Output the case number counting from 1 in the first line.<br/>
  Then M blocks follow, each contains Ri (or less, see next) lines. Each line should contain exactly Ci characters. Use space (ASCII 32) to fill in the blank. But if a line contains only whitespaces, this line should not be outputted.<br/>
  Output a blank line after each graph fragment.<br/>
</span></div>
<div class="panel_content">
<pre></pre>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3<br/>
3 1 2<br/>
1<br/>
1 1 5 3<br/>
6 4 5 6 1 3 2<br/>
1<br/>
1 1 8 10<br/>
10<br/>
2 6 7 4 5 3 1 9 10 8<br/>
2<br/>
1 1 5 5<br/>
3 6 5 5<br/>
 <br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1:<br/>
+-o<br/>
|  <br/>
o+ <br/>
 | <br/>
 o <br/>
<br/>
Case #2:<br/>
+--o+     <br/>
|   |     <br/>
o-+ o+    <br/>
  |  |    <br/>
 +o  o    <br/>
 |        <br/>
 o        <br/>
<br/>
Case #3:<br/>
+o---<br/>
|    <br/>
o  +-<br/>
   | <br/>
  +o+<br/>
<br/>
o+   <br/>
 |   <br/>
 o-+ <br/>
   | <br/>
  +o+<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Acm 2011 上海">Acm 2011 上海</a></p></div>

