<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>N个节点的有向图, 求从start到finish刚好经过时间time的总方案数 mod 502630.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数n, 所有点是从0到N-1编号.</p>
<p>       接下来n行,每行包含n个字符. 第i行第j个字符表示i到j需要的时间. 字符只可能是’1’到’5’, 或者是’.’表示i不能到达j. 保证主对角线都是’.’.</p>
<p>       接下来一行3个整数start, finish, time.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出总方案数.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>       3</p>
<p>       .12</p>
<p>       2.1</p>
<p>       12.</p>
<p>       0 2 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>       对于20%的数据, 输入的字符不是’1’就是’.’;</p>
<p>       对于100%的数据, 1 &lt;= n &lt;= 10; 1 &lt;= start,finish &lt;= n; 1 &lt;= time &lt;= 10^9.</p>
</div>
</div>