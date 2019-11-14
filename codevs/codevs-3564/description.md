<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一个阶梯形棋盘，放上尽量少的“车”，控制所有的格子。一个“车”可以控制和它在同一行和同一列的所有格子。所谓“阶梯”型棋盘，指的是，每行的格子只出现在一些连续的列上。从第二行开始，每行的起始列数不小于上一行的起始列数，且终止列数也不小于上一行的终止列数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入数据有p+1行</p><p>第一行：给出梯形棋盘列的个数p(0&lt;p&lt;=100)</p><p>从2～p+1行，每行有两个数t,x,y(0&lt;t,x,y&lt;=100),分别表示从第t列第x行起，竖着数，有y个格子。</p><p><br></p><p>输入数据保证严格遵守阶梯型棋盘的性质。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行输出一个数ans，表示最少需要多少个车。</p><p>从2～ans+1行，每行输出两个数i,j，表示车所在的位置。</p><p><br/></p><p>（Attention：棋盘左上角格子的坐标为(1,1)，下面一个格子的坐标为（2,1），右面一个格子的坐标为（1,2））</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6<br></p><p>1 1 3</p><p>2 1 3</p><p>3 1 5</p><p>4 3 3</p><p>5 3 3</p><p>6 4 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见输入输出描述。</p>
</div>
</div>