
# Description

<div class="content"><p><span style="font-size: medium">我们知道一棵有根树可以进行深度优先遍历（DFS）以及广度优先遍历（BFS）来生成这棵树的DFS序以及BFS序。两棵不同的树的DFS序有可能相同，并且它们的BFS序也有可能相同，例如下面两棵树的DFS序都是1 2 4 5 3，BFS序都是1 2 3 4 5</span></p>
<p><span style="font-size: medium"><img height="305" width="438" alt="" src="/source/bzoj/3244/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNy9hYS5wbmc=.png"/></span></p>
<p><span style="font-size: medium">现给定一个DFS序和BFS序，我们想要知道，符合条件的有根树中，树的高度的平均值。即，假如共有K棵不同的有根树具有这组DFS序和BFS序，且他们的高度分别是h1,h2,...,hk，那么请你输出<br/>
(h1+h2..+hk)/k </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">有3行。 <br/>
第一行包含1个正整数n，表示树的节点个数。 <br/>
第二行包含n个正整数，是一个1~n的排列，表示树的DFS序。 <br/>
第三行包含n个正整数，是一个1~n的排列，表示树的BFS序。 <br/>
输入保证至少存在一棵树符合给定的两个序列。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">仅包含1个实数，四舍五入保留恰好三位小数，表示树高的平均值。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
5 <br/>
1 2 4 5 3 <br/>
1 2 3 4 5<br/>
<br/>
		</span></div>

# Sample Output

<div class="content"><span class="sampledata">3.500</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【评分方式】<br/><br/>
如果输出文件的答案与标准输出的差不超过0.001，则将获得该测试点上的分数，否则不得分。<br/><br/>
【数据规模和约定】<br/><br/>
<br/><br/>
20%的测试数据，满足：n≤10；<br/><br/>
40%的测试数据，满足：n≤100；<br/><br/>
85%的测试数据，满足：n≤2000；<br/><br/>
100%的测试数据，满足：2≤n≤200000。<br/><br/>
【说明】<br/><br/>
树的高度：一棵有根树如果只包含一个根节点，那么它的高度为1。否则，它的高度为根节点的所有子树的高度的最大值加1。<br/><br/>
对于树中任意的三个节点a , b , c ，如果a, b都是c的儿子，则a, b在BFS序中和DFS序中的相对前后位置是一致的，即要么a都在b的前方，要么a都在b的后方。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

