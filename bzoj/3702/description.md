
# Description

<div class="content"><p><span style="font-size: medium">现在有一棵二叉树，所有非叶子节点都有两个孩子。在每个叶子节点上有一个权值(有n个叶子节点，满足这些权值为1..n的一个排列)。可以任意交换每个非叶子节点的左右孩子。<br/>
要求进行一系列交换，使得最终所有叶子节点的权值按照中序遍历写出来，逆序对个数最少。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行n<br/>
下面每行，一个数x<br/>
如果x==0，表示这个节点非叶子节点，递归地向下读入其左孩子和右孩子的信息，<br/>
如果x!=0，表示这个节点是叶子节点，权值为x。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">一行，最少逆序对个数。<br/>
</font></p></div>

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

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据：2&lt;=n&lt;=200000。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

