
# Description

<div class="content">As  you  are  bound  to  know  by  now,  a  tree  is  a  connected  graph
consisting  of N  vertices  and N−1 edges. Trees  also  have  the  property
of  there  being  exactly  a  single  unique path  between  any  pair  of 
vertices. 
You will be given a tree in which every edge is assigned a weight – 
a non negative integer. The weight of a path is the product of the
weights of all edges on the path. The weight of the tree is the sum of 
the  weights  of  all  paths  in  the  tree.  Paths  going  in  opposite
directions  (A  to  B  and  B  to  A)  are considered the same and, when 
calculating the weight of a tree, are counted only once. 
Write a program that, given a tree, calculates its weight modulo 1000000007. 
</div>

# Input

<div class="content">The first line contains the integer N (2 ≤ N ≤ 100 000), the number of vertices
in the tree. The vertices are numbered 1 to N. Each  of  the  following N−1
contains  three  integers A,  B  and W  (1 ≤ A,  B ≤ N,  0 ≤ W ≤  1000) 
describing one edge. The edge connects vertices A and B, and its weight is W.

</div>

# Output

<div class="content">Output the weight of the tree, modulo 1000000007. 

</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 <br/>
3 2 100 <br/>
2 1 100 <br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
10200 <br/>
</span></div>

# Hint

<div class="content"><p>The weight of the path from 1 to 2 is 100 <br/>
The weight of the path from 2 to 3 is 100 <br/>
The weight of the path from 1 to 3 is 100 * 100 = 10000 <br/>
So the weight of the tree is 10000 + 100 + 100 = 10200 </p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

