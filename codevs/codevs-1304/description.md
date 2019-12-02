<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>求一颗有根树/树形图的拓扑序个数.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个n和一个素数P,表示这颗树有n个节点,要求拓扑序个数modP之后的结果.</p>
<p>接下来n-1行,每行有两个数字x和y,表示x是y的父亲.</p>
<p>保证1&lt;=n&lt;=1500000, n&lt;P&lt;2^31,P为质数.</p>
<p> </p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个数字,为该树形图拓扑序个数modP的结果.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1<br>4 100000007<br>1 2<br>1 3<br>2 4<br><br>样例2<br>6 100000007<br>1 2<br>2 3<br>1 4<br>3 5<br>5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1<br>3<br><br>样例2<br>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>每个非根节点的儿子个数平均较多,数据量较大,建议c/c++选手才用scanf的读入方式</p>
</div>
</div>