
# Description

<div class="content"><p>Byteasar the gardener is growing a rare tree called Rotatus Informatikus. It has some interesting features: The tree consists of straight branches, bifurcations and leaves. The trunk stemming from the ground is also a branch. Each branch ends with either a bifurcation or a leaf on its top end. Exactly two branches fork out from a bifurcation at the end of a branch - the left branch and the right branch. Each leaf of the tree is labelled with an integer from the range . The labels of leaves are unique. With some gardening work, a so called rotation can be performed on any bifurcation, swapping the left and right branches that fork out of it. The corona of the tree is the sequence of integers obtained by reading the leaves&#39; labels from left to right. Byteasar is from the old town of Byteburg and, like all true Byteburgers, praises neatness and order. He wonders how neat can his tree become thanks to appropriate rotations. The neatness of a tree is measured by the number of inversions in its corona, i.e. the number of pairs（I,j）, (1&lt; = I &lt; j &lt; = N ) such that(Ai&gt;Aj) in the corona(A1,A2,A3…An). <img border="0" alt="" src="/source/bzoj/2212/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIyMTIuanBn.jpg"/> The original tree (on the left) with corona(3,1,2) has two inversions. A single rotation gives a tree (on the right) with corona(1,3,2), which has only one inversion. Each of these two trees has 5 branches. Write a program that determines the minimum number of inversions in the corona of Byteasar&#39;s tree that can be obtained by rotations.</p>
<p>现在有一棵二叉树，所有非叶子节点都有两个孩子。在每个叶子节点上有一个权值(有n个叶子节点，满足这些权值为1..n的一个排列)。可以任意交换每个非叶子节点的左右孩子。<br/>
要求进行一系列交换，使得最终所有叶子节点的权值按照遍历序写出来，逆序对个数最少。</p>
<p></p></div>

# Input

<div class="content"><p>In the first line of the standard input there is a single integer (2&lt; = N &lt; = 200000) that denotes the number of leaves in Byteasar&#39;s tree. Next, the description of the tree follows. The tree is defined recursively: if there is a leaf labelled with ()(1&lt;=P&lt;=N) at the end of the trunk (i.e., the branch from which the tree stems), then the tree&#39;s description consists of a single line containing a single integer , if there is a bifurcation at the end of the trunk, then the tree&#39;s description consists of three parts: the first line holds a single number , then the description of the left subtree follows (as if the left branch forking out of the bifurcation was its trunk), and finally the description of the right subtree follows (as if the right branch forking out of the bifurcation was its trunk).</p>
<p>第一行n<br/>
下面每行，一个数x<br/>
如果x==0，表示这个节点非叶子节点，递归地向下读入其左孩子和右孩子的信息，<br/>
如果x!=0，表示这个节点是叶子节点，权值为x</p>
<p>1&lt;=n&lt;=200000</p>
<p></p></div>

# Output

<div class="content"><p>In the first and only line of the standard output a single integer is to be printed: the minimum number of inversions in the corona of the input tree that can be obtained by a sequence of rotations.</p>
<p>一行，最少逆序对个数</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0<br/>
0<br/>
3<br/>
1<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

