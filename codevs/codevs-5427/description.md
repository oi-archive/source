<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>xzy被他的高一学弟zgx鬼了，感到不爽。</p><p>他把zgx放到了一个迷宫里。迷宫的墙上有一个长度为N的数列A，通过它可以求出从迷宫逃脱的密码。我们任意取一个区间[L,R](L&lt;=R)，定义它的分值为这个区间内的最小值，那么密码就是所有不重复的区间的分值和。</p><p>作为一个提示，xzy告诉zgx，用栈就可以破解出这个密码。请你求出这个密码。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个数N，接下来一行有N个数，第i个数表示数列的第i项。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一个数，表示你求出的密码。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>1 2 3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：</p><p>一共有六个不重复的区间，分别为[1,1],[2,2],[3,3],[1,2],[1,3],[2,3]</p><p>它们的分值分别为1,2,3,1,1,2</p><p>因此密码为1+2+3+1+1+2=10。</p><p><br></p><p>数据范围：</p><p>N&lt;=500000，数列中每个数不超过1000。<br></p>
</div>
</div>