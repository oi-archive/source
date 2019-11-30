<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">ZZJ一直仰慕的左女神有时候会迷路。这一天，左女神从XJTU出发前往某土豪区买最新发售的Iphone 7，然而却在某个地方迷路了。ZZJ得知这个消息之后想能够尽快地找到左女神，以提高好感度。如何快速地找到左女神的位置，这个问题现在焦头烂额的ZZJ决定请你来帮忙，他需要你编写一个程序来计算按怎样的路线搜索效率最高。</span></p><p style=""><span style="">为了将问题简单化，可以我们把XJTU附近的街道看作一棵树，每一个地点看作一个节点，XJTU作为根节点，所有的节点从1到n编号，根节点是1号节点。现在已知所有的地点之间的道路，也就是树上的边，每条边的长度都视为1。同时我们还知道左女神位于某一个叶子节点的位置，但是并不知道是哪一个叶子节点。你需要计算出一个搜索或者说遍历方案，来让ZZJ找到左女神所需要走的距离的总期望值最小。当然，这个方案得从XJTU出发，也就是根节点出发。</span></p><p style=""><span style="">PS：期望值等于左女神在某个叶子节点的几率，乘上这种情况下以你设计的搜索方案来达到那个叶子节点所要走的距离。总期望值也就是考虑左女神在每一个叶子节点的情况下，以你设计的搜索方案搜索的期望值的总和。</span></p><p style=""><span style="">具体参考样例数据及分析</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含一个整数 n，表示一共有n个地点。</span></p><p style=""><span style="">接下来的n-1行，每一行两个整数a、b，表示a，b两地点之间有道路连接。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="background: white;"><span style="font-size:16px;font-family:&#39;微软雅黑&#39;,&#39;sans-serif&#39;">输出共一行，包含一个整数a，a为最小总期望值与叶子节点个数的积。</span></p><p style="background: white;"></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">7 <br> 1 2</span></p><p style=""><span style="">1 3</span></p><p style=""><span style="">1 4</span></p><p style=""><span style="">2 5</span></p><p style=""><span style="">3 6</span></p><p style=""><span style="">3 7</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">21</span></p><p style=""><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【样例说明】</span></p><p style=""><span style="">如上图<br>从根节点出发</span></p><p style=""><span style="">最优的搜索方案，也就是叶子节点的访问顺序是4-6-7-5（或者4-7-6-5）</span></p><p style=""><span style="">女神在5号节点的几率是1/4，按此方案搜索到5的路程是10，期望值为10/4</span></p><p style=""><span style="">女神在6号节点的几率是1/4，按此方案搜索到6的路程是4，期望值为4/4</span></p><p style=""><span style="">女神在7号节点的几率是1/4，按此方案搜索到7的路程是6，期望值为6/4</span></p><p style=""><span style="">女神在4号节点的几率是1/4，按此方案搜索到4的路程是1，期望值为1/4</span></p><p style=""><span style="">总期望值为 (10+4+6+1)/4=21/4</span></p><p style=""><span style="">答案为 总期望值×叶子节点数 = 21/4 * 4 = 21</span></p><p style=""><span style=""><br> </span><span style="">【数据范围】</span></p><p style=""><span style="">&lt;font face="微软雅黑, sans-serif"&gt;<span style="">对于  20</span><span style="">%</span><span style="">的数据，</span><span style="">n </span><span style="">≤ 20</span>&lt;/font&gt;</span></p><p style=""><span style="">对于  50</span><span style="">%</span><span style="">的数据，</span><span style="">n </span><span style="">≤ 2,000</span></p><p style=""><span style=""> </span><span style=""></span><span style="">对于  100</span><span style="">%</span><span style="">的数据，</span><span style="">n </span><span style="">≤ 100,000</span><span style=""></span></p><p><br></p>
</div>
</div>