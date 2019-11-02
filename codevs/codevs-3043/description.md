<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　我们知道一棵有根树可以进行深度优先遍历（DFS）以及广度优先遍历（BFS）来生成这棵树的DFS序以及BFS序。两棵不同的树的DFS序有可能相同，并且它们的BFS序也有可能相同，例如下面两棵树的DFS序都是1 2 4 5 3，BFS序都是1 2 3 4 5。</p>
<p> <img height="305" src="../../../media/image/problem/3043.jpg" style="" width="438"></p>
<p>　　现给定一个DFS序和BFS序，我们想要知道，符合条件的有根树中，树的高度的平均值。即，假如共有K棵不同的有根树具有这组DFS序和BFS序，且他们的高度分别是h<sub>1</sub>,h<sub>2</sub>,...,h<sub>k</sub>，那么请你输出：</p>
<p><img height="57" src="../../../media/image/problem/3043_1.jpg" style="" width="136"></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　输入共有3行。</p>
<p>　　第一行包含1个正整数n，表示树的节点个数。</p>
<p>　　第二行包含n个正整数，是一个1~n的排列，表示树的DFS序。</p>
<p>　　第三行包含n个正整数，是一个1~n的排列，表示树的BFS序。</p>
<p>　　输入保证至少存在一棵树符合给定的两个序列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　输出仅包含1个实数，四舍五入保留恰好三位小数，表示树高的平均值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>【</span>样例输入 1<span>】</span></p>
<p>5<br>1 2 4 5 3<br>1 2 3 4 5</p>
<p> </p>
<p><span>【</span>样例输入 2<span>】</span></p>
<p>90<br>20 70 23 8 61 38 64 34 32 12 36 77 29 26 44 55 83 42 22 87 15 1 19 18 63 9 35 41 31 48 28 76 86 84 17 49 10 7 30 37 4 74 45 39 56 75 6 72 25 21 33 65 27 66 5 82 78 80 2 79 11 46 71 40 69 47 88 57 13 24 81 68 16 50 90 62 14 51 85 89 60 54 67 52 53 43 73 59 3 58<br>20 70 23 8 61 38 64 34 32 36 12 77 29 26 44 55 83 42 22 15 87 1 19 63 35 41 18 9 31 48 28 76 86 84 17 49 10 7 30 37 4 74 45 39 56 75 6 72 25 21 33 65 27 66 5 82 78 80 2 79 11 46 71 40 69 47 88 57 13 24 81 68 16 50 90 62 14 51 85 89 60 54 67 52 53 43 73 59 3 58</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出 1】</p>
<p>3.500</p>
<p> </p>
<p>【样例输出 2】</p>
<p>43.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【评分方式】</span></p>
<p><span>　　如果输出文件的答案与标准输出的差不超过0.001，则将获得该测试点上的分数，否则不得分。</span></p>
<p><span><br></span></p>
<p><span>【数据规模和约定】</span></p>
<p><span>　　20%的测试数据，满足：n≤10；</span></p>
<p><span>　　40%的测试数据，满足：n≤100；</span></p>
<p><span>　　85%的测试数据，满足：n≤2000；</span></p>
<p><span>　　100%的测试数据，满足：2≤n≤200000。</span></p>
<p><span><br></span></p>
<p><span>【说明】</span></p>
<p><span>　　树的高度：一棵有根树如果只包含一个根节点，那么它的高度为1。否则，它的高度为根节点的所有子树的高度的最大值加1。</span><br><span>　　对于树中任意的三个节点a , b , c ，如果a, b都是c的儿子，则a, b在BFS序中和DFS序中的相对前后位置是一致的，即要么a都在b的前方，要么a都在b的后方。</span></p>
</div>
</div>