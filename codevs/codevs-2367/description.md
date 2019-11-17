<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有向图 G有n个顶点 1, 2, …, n，点i 的权值为 w(i)。现在有一只蚂蚁，从给定的起点 v0出发，沿着图 G 的边爬行。开始时，它的体力为 1。每爬过一条边，它的体力都会下降为原来的 ρ 倍，其中ρ 是一个给定的小于1的正常数。而蚂蚁爬到某个顶点时的幸福度，是它当时的体力与该点权值的乘积。 我们把蚂蚁在爬行路径上幸福度的总和记为 H。很显然，对于不同的爬行路径，H 的值也可能不同。小 Z 对 H 值的最大可能值很感兴趣，你能帮助他计算吗？注意，蚂蚁爬行的路径长度可能是无穷的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行包含两个正整数 n, m，分别表示 G 中顶点的个数和边的条<br>数。 <br>第二行包含 n个非负实数，依次表示 n个顶点权值 w(1), w(2), …, w(n)。 <br>第三行包含一个正整数 v0，表示给定的起点。 <br>第四行包含一个实数 ρ，表示给定的小于 1的正常数。 <br>接下来 m行，每行两个正整数 x, y，表示&lt;x, y&gt;是G的一条有向边。可能有<br>自环，但不会有重边。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个实数，即 H值的最大可能值，四舍五入到小数<br />点后一位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 <br>10.0 8.0 8.0 8.0 15.0 <br>1 <br>0.5 <br>1 2 <br>2 3 <br>3 4 <br>4 2 <br>4 5 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>18.0 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20%的数据，ρ ≤0.5； <br>另有 20%的数据，保证 H的最大值在有限路径上取到； <br>对于 100%的数据， n ≤ 100， m ≤ 1000， ρ ≤ 1 – 10-6， w(i) ≤ 100 (i = 1, 2, …, n)。</p>
</div>
</div>