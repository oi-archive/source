<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近，小栋在无向连通图的生成树个数计算方面有了惊人的进展，他发现： ·n 个结点的环的生成树个数为 n。 ·n 个结点的完全图的生成树个数为 nn-2。 这两个发现让小栋欣喜若狂，由此更加坚定了他继续计算生成树个数的想 法，他要计算出各种各样图的生成树数目。 一天，小栋和同学聚会，大家围坐在一张大圆桌周围。小栋看了看，马上想 到了生成树问题。如果把每个同学看成一个结点，邻座（结点间距离为 1）的同 学间连一条边，就变成了一个环。可是，小栋对环的计数已经十分娴熟且不再感 兴趣。于是，小栋又把图变了一下：不仅把邻座的同学之间连一条边，还把相隔 一个座位（结点间距离为 2）的同学之间也连一条边，将结点间有边直接相连的 这两种情况统称为有边相连，如图 1 所示。 </p>
<p>小栋以前没有计算过这类图的生成树个数，但是，他想起了老师讲过的计算 任意图的生成树个数的一种通用方法：构造一个 n×n 的矩阵 A={aij} ，其中</p>
<p>a<sub>ij</sub>=d<sub>i     </sub>i = j</p>
<p>a<sub>ij</sub>=-1    i与j有边相连</p>
<p>a<sub>ij</sub>=0     其它</p>
<p>其中 di表示结点 i 的度数。</p>
<p>与图 1 相应的 A 矩阵如下所示。为了计算图 1 所对应的生成数的个数，只要 去掉矩阵 A 的最后一行和最后一列，得到一个(n-1)×(n-1)的矩阵 B，计算出矩阵 B 的行列式的值便可得到图 1 的生成树的个数。 <br><br></p>
<p>见图2，所以生成树的个数为 3528 =B 。小栋发现利用通用方法，因计算过于复杂而很难算出来，而且用其他方法也难以找到更简便的公式进行计算。于是，他将图做了简化，从一个地方将圆桌断开，这样所有的同学形成了一条链，连接距离 为 1 和距离为 2 的点。例如八个点的情形如图3： <br>这样生成树的总数就减少了很多。小栋不停的思考，一直到聚会结束，终于 找到了一种快捷的方法计算出这个图的生成树个数。可是，如果把距离为3 的点也连起来，小栋就不知道如何快捷计算了。现在，请你帮助小栋计算这类图的生成树的数目。</p>

<img src="/source/codevs/codevs-1799/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzk5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc5OV8xLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中包含两个整数 k, n，由一个空格分隔。k 表示要将所有距离不超 过 k（含 k）的结点连接起来，n 表示有 n 个结点。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件输出一个整数，表示生成树的个数。由于答案可能比较大，所以你 只要输出答案除 65521 的余数即可。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>75</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释与提示详见图中。</p>
<p>数据规模和约定：<br>对于所有的数据 2≤ k≤ n，</p>
<table border="0">
<tbody>
<tr>
<td>数据编号</td>
<td>k范围</td>
<td>n范围</td>
</tr>
<tr>
<td>1</td>
<td>=2</td>
<td><span>≤10</span></td>
</tr>
<tr>
<td>2</td>
<td>=3</td>
<td>=5</td>
</tr>
<tr>
<td>3</td>
<td>=4</td>
<td><span>≤10</span></td>
</tr>
<tr>
<td>4</td>
<td>=5</td>
<td>=10</td>
</tr>
<tr>
<td>5</td>
<td>≤3</td>
<td><span>≤100</span></td>
</tr>
<tr>
<td>6</td>
<td>≤5</td>
<td><span>≤100</span></td>
</tr>
<tr>
<td>7</td>
<td><span>≤3</span></td>
<td><span>≤2000</span></td>
</tr>
<tr>
<td>8</td>
<td><span>≤5</span></td>
<td><span>≤10000</span></td>
</tr>
<tr>
<td>9</td>
<td><span>≤3</span></td>
<td>≤10<sup>15</sup></td>
</tr>
<tr>
<td>10</td>
<td><span>≤5</span></td>
<td>≤10<sup>15</sup></td>
</tr>
</tbody>
</table>
</div>
</div>