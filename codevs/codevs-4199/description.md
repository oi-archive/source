<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近奶牛们喜欢上了一个叫“Moo”的游戏。这个游戏是这样玩的：所有的牛排成一条直线，每只在队列里的牛都有责任尽可能快的叫出一个特定的字符。在 Moo 游戏中，奶牛们吼叫的字符序列是有规律可循的，这个序列是这样开始的：</p><p>m o o m o o o m o o m o o o o m o o m o o o m o o m o o o o o</p><p>这个序列可以被递归描述为：S（0）是一个三个字符的序列“Moo”，S（K）=S（K-1）Moo....ooS（K-1)，其中 o 有 K+2 个。例如：</p><p>S(0) = "m o o"</p><p>S(1) = "m o o m o o o m o o"</p><p>S(2) = "m o o m o o o m o o m o o o o m o o m o o o m o o"</p><p>现在要你计算第 N 头奶牛要叫出“m”还是“o”。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行一个正整数 N。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只输出一个字符，“m”或者“o”。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>m<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=N&lt;=1000000000。</p><p>保证不会爆内存<br></p>
</div>
</div>