<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    一个无向连通图，顶点从 1 编号到 N，边从 1 编号到 M。 <br>    小 Z 在该图上进行随机游走，初始时小 Z 在 1 号顶点，每一步小 Z 以相等的概率随机选择当前顶点的某条边，沿着这条边走到 下一个顶点，获得等于这条边的编号的分数。当小 Z到达 N 号顶点时游走结束，总分为所有获得的分数之和。 <br>    现在，请你对这 M 条边进行编号，使得小 Z 获得的总分的期望值最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件第一行是正整数N和M，分别表示该图的顶点数和边数，接下来M行每行是整数u，v(1≤u,v≤N)，表示顶点u与顶点v之间存在一条边。 <br>    输入保证30%的数据满足N≤10，100%的数据满足2≤N≤500且是一个无向简单连通图。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个实数，表示最小的期望值，保留 3 位小数。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 <br>2 3 <br>1 2 <br>1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3.333 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> 边(1,2)编号为1，边(1,3)编号2，边(2,3)编号为3。 </p>
</div>
</div>