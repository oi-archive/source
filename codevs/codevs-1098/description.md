<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>有 N 堆纸牌，编号分别为 1，2，…, N。每堆上有若干张，但纸牌总数必为 N 的倍数。可以在任一堆上取若于张纸牌，然后移动。<br>　　移牌规则为：在编号为 1 堆上取的纸牌，只能移到编号为 2 的堆上；在编号为 N 的堆上取的纸牌，只能移到编号为 N-1 的堆上；其他堆上取的纸牌，可以移到相邻左边或右边的堆上。<br>　　现在要求找出一种移动方法，用最少的移动次数使每堆上纸牌数都一样多。<br><br>　　例如 N=4，4 堆纸牌数分别为：<br>　　①　9　②　8　③　17　④　6<br>　　移动3次可达到目的：<br>　　从 ③ 取 4 张牌放到 ④ （9 8 13 10） -&gt; 从 ③ 取 3 张牌放到 ②（9 11 10 10）-&gt; 从 ② 取 1 张牌放到①（10 10 10 10）。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行N（N 堆纸牌，1 &lt;= N &lt;= 100）<br>第二行A1 A2 … An （N 堆纸牌，每堆纸牌初始数，l&lt;= Ai &lt;=10000）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span lang="EN-US">输出至屏幕。格式为：<br />所有堆均达到相等时的最少移动次数。&lsquo;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4<br>9 8 17 6</span></p>

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
<p>e</p>
</div>
</div>