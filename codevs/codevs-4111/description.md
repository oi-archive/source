<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Jijijie是恐怖的科学怪人,他有特殊的邪恶科技 Song'ci Crash。Dash在他的家庭农场里拥有n块连续的拥有者黑色和金色混杂的Da’shgua田地。</p><p>Song'ci Crash攻击会使连续的一段Da'shgua田地遭受打击,会使编号在[L, R]范围内的田地产量从a变为 [ln(a)]([]表示向下取整)。</p><p>tty,Long'Aotian职阶的骑士,将驾驶他的knightmare,tgopknight,来迎战。</p><p>tty每夺回一块Da'shgua田地,这块田地就会在Owaski天神的庇护下获得生机,使田地产量突变。</p><p>国王Papafish急不可耐地想知道战况如何,他会询问连续的一段Da'shgua田地的产量之和。</p><p>机智的你,能回答他的询问吗?</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行两个正整数 n, m 分别表示田地的个数和操作个数</p><p>第2行n个非负整数, 第i个数表示序列的第i个元素a[i]</p><p>第3行到第 M + 2行, 每行三个正整数 op, x, y</p><p>op = 1, 表示夺回x田地,使田地x产量突变为y, 1 &lt;= x &lt;= N, 1 &lt;= y &lt;= 10^9</p><p>op = 2, 表示Song’ci Crash攻击,攻击范围为[x, y], 1 &lt;= x, y &lt;= N</p><p>op = 3, 表示Papafish的询问,询问范围为[x, y], 1 &lt;= x, y &lt;= N</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个Papafish的询问,&nbsp;输出一行,表示答案。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 5</p><p>1 3 3</p><p>3 1 3</p><p>1 2 1</p><p>3 2 3</p><p>2 2 3</p><p>3 1 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p><p>4</p><p>2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><img src="/source/codevs/codevs-4111/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MTExL2h0dHBzOi8vZG4tY29kZXZzLXRlc3RpbmcucWJveC5tZS9pbWcvQ19EYXRhX1JhbmdlLnBuZz9pbWFnZVZpZXcyLzIvdy83MDA=.png"></p>
</div>
</div>