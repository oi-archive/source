<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Farmer John为了保持奶牛们的健康，让可怜的奶牛们不停在牧场之间<br> 的小路上奔跑。这些奶牛的路径集合可以被表示成一个点集和一些连接<br> 两个顶点的双向路，使得每对点之间恰好有一条简单路径。简单的说来，<br> 这些点的布局就是一棵树，且每条边等长，都为1。<br> <br> 对于给定的一个奶牛路径集合，精明的奶牛们会计算出任意点对路径的最大值，<br> 我们称之为这个路径集合的直径。如果直径太大，奶牛们就会拒绝锻炼。<br> <br> Farmer John把每个点标记为1..V (2 &lt;= V &lt;= 100,000)。为了获得更加短<br> 的直径，他可以选择封锁一些已经存在的道路，这样就可以得到更多的路径集合，<br> 从而减小一些路径集合的直径。<br> <br> 我们从一棵树开始，FJ可以选择封锁S (1 &lt;= S &lt;= V-1)条双向路，从而获得<br> S+1个路径集合。你要做的是计算出最佳的封锁方案，使得他得到的所有路径集合<br> 直径的最大值尽可能小。<br> <br> Farmer John告诉你所有V-1条双向道路，每条表述为：顶点A_i (1 &lt;= A_i &lt;= V) <br> 和 B_i (1 &lt;= B_i &lt;= V; A_i!= B_i)连接。</p>
<p>我们来看看如下的例子：</p>
<p>线性的路径集合(7个顶点的树)<br> <br>                    </p>
<p>1---2---3---4---5---6---7</p>
<p>如果FJ可以封锁两条道路，他可能的选择如下：<br> <br>           </p>
<p>1---2 | 3---4 | 5---6---7</p>
<p> </p>
<p>这样最长的直径是2，即是最优答案(当然不是唯一的)。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第1行： 两个空格分隔的整数V和S</p>
<p>* 第2...V行： 两个空格分隔的整数A_i和B_i</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">* 第1行：一个整数，表示FJ可以获得的最大的直径。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 2</p>
<p>6 7</p>
<p>3 4</p>
<p>6 5</p>
<p>1 2</p>
<p>3 2</p>
<p>4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于50%的数据，满足V&lt;=100；</p>
<p>对于100%的数据，满足V&lt;=100000</p>
</div>
</div>