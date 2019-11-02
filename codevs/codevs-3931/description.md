<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>所谓的异或图是一个这样无向图：它有N个点，依次标号为1..N，对于三个标号分别为a,b,c的点，如果a异或b异或c=0，那么这三个点之间两两连边，这是异或图连边的充要条件。此时把这张异或图的无向边的条数记为V(N)，对于给定的L，R，满足L&lt;=R，试求V(L)+V(L+1)+...+V(R-1)+V(R)的值，由于结果可能很大，请将其对M取模后输出。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>本题有多组数据。</p><p>第一行，一个正整数T，表示测试数据的组数。</p><p>接下来T行，每行三个正整数L，R，M，相邻两数之间有一个空格。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共T行，每行输出该组数据的答案对M取模后的结果。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>1 4 100</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>V(1)=V(2)=0，V(3)=V(4)=3，因此样例中的答案是6。</p><p>1&lt;=T&lt;=50,000，1&lt;=L,R,M&lt;=1,000,000,000。</p>
</div>
</div>