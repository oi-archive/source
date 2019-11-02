<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>H </span><span>国有 </span><span>n </span><span>个城市，这 </span><span>n </span><span>个城市用 </span><span>n-1 </span><span>条双向道路相互连通构成一棵树，</span><span>1 </span><span>号城市是首都，</span></p>
<p><span>也是树中的根节点。</span></p>
<p><span>H </span><span>国的首都爆发了一种危害性极高的传染病。当局为了控制疫情，不让疫情扩散到边境</span></p>
<p><span>城市（叶子节点所表示的城市），决定动用军队在一些城市建立检查点，使得从首都到边境</span></p>
<p><span>城市的每一条路径上都至少有一个检查点，边境城市也可以建立检查点。但特别要注意的是，</span></p>
<p><span>首都是不能建立检查点的。</span></p>
<p><span>现在，在 </span><span>H</span><span>国的一些城市中已经驻扎有军队，且一个城市可以驻扎多个军队。一支军</span></p>
<p><span>队可以在有道路连接的城市间移动，并在除首都以外的任意一个城市建立检查点，且只能在</span></p>
<p><span>一个城市建立检查点。一支军队经过一条道路从一个城市移动到另一个城市所需要的时间等</span></p>
<p><span>于道路的长度（单位：小时）。</span></p>
<p><span>请问最少需要多少个小时才能控制疫情。注意：不同的军队可以同时移动。</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行一个整数 </span><span>n</span><span>，表示城市个数。</span></p>
<p><span>接下来的 </span><span>n-1 </span><span>行，每行 </span><span>3 </span><span>个整数，</span><span>u</span><span>、</span><span>v</span><span>、</span><span>w</span><span>，每两个整数之间用一个空格隔开，表示从</span></p>
<p><span>城市 </span><span>u </span><span>到城市 </span><span>v </span><span>有一条长为 </span><span>w </span><span>的道路。数据保证输入的是一棵树，且根节点编号为 </span><span>1</span><span>。</span></p>
<p><span>接下来一行一个整数 </span><span>m</span><span>，表示军队个数。</span></p>
<p><span>接下来一行 </span><span>m </span><span>个整数，每两个整数之间用一个空格隔开，分别表示这 </span><span>m </span><span>个军队所驻扎</span></p>
<p><span>的城市的编号。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>共一行，包含一个整数，表示控制疫情所需要的最少时间。如果无法控制疫情则输出</span><span>-1</span><span>。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 </span></p>
<p><span>1 2 1 </span></p>
<p><span>1 3 2 </span></p>
<p><span>3 4 3 </span></p>
<p><span>2 </span></p>
<p><span>2 2 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p><span>【输入输出样例说明】</span></p>
<p>第一支军队在 2 号点设立检查点，第二支军队从 2 号点移动到 3 号点设立检查点，所需</p>
</div>
<div>
<p><span>时间为 </span><span>3 </span><span>个小时。</span></p>
<p> </p>
<p><span>【数据范围】</span></p>
<p><span>保证军队不会驻扎在首都。</span></p>
<p><span>对于 </span><span>20%</span><span>的数据，</span><span>2≤ n≤ 10</span><span>；</span></p>
<p><span>对于 </span><span>40%</span><span>的数据，</span><span>2 ≤n≤50</span><span>，</span><span>0&lt;w &lt;10^</span><span>5</span><span>；</span></p>
<p><span>对于 </span><span>60%</span><span>的数据，</span><span>2 ≤ n≤1000</span><span>，</span><span>0&lt;w &lt;10^</span><span>6</span><span>；</span></p>
<p><span>对于 </span><span>80%</span><span>的数据，</span><span>2 ≤ n≤10,000</span><span>；</span></p>
<p><span>对于 </span><span>100%</span><span>的数据，</span><span>2≤m≤n≤50,000</span><span>，</span><span>0&lt;w &lt;10^</span><span>9</span><span>。</span></p>
</div>
</div>
</div>