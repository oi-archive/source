
# Description

<div class="content"><div><span style="font-size: medium">　　红黑树是一类特殊的二叉搜索树，其中每个结点被染成红色或黑色。若将二叉搜索树结点中的空指针看作是指向一个空结点，则称这类空结点为二叉搜索树的前端结点。并规定所有前端结点的高度为-1。</span></div>
<div><span style="font-size: medium">　　一棵红黑树是满足下面“红黑性质”的染色二叉搜索树：</span></div>
<div><span style="font-size: medium">　　(1) 每个结点被染成红色或黑色；</span></div>
<div><span style="font-size: medium">　　(2) 每个前端结点为黑色结点；</span></div>
<div><span style="font-size: medium">　　(3) 任一红结点的子结点均为黑结点；</span></div>
<div><span style="font-size: medium">　　(4) 在从任一结点到其子孙前端结点的所有路径上具有相同的黑结点数。</span></div>
<div><span style="font-size: medium">　　从红黑树中任一结点x出发(不包括结点x)，到达一个前端结点的任意一条路径上的黑结点个数称为结点x的黑高度，记作bh(x)。红黑树的黑高度定义为其根结点的黑高度。</span></div>
<div><span style="font-size: medium">　　给定正整数N，试设计一个算法，计算出在所有含有N个结点的红黑树中，红色内结点个数的最小值和最大值。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">　　输入共一个数N。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">　　输出共两行。</span></div>
<div><span style="font-size: medium">　　第一行为红色内结点个数的最小值，第二行为最大值。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
8<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
1<br/>
4<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于 100% 的数据，1≤N≤5000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

