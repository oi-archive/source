<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>毛大神最近在研究一个全零矩阵游戏，但是遇到了瓶颈时没有头绪所以特请你来帮忙。</p><p> 有一个N行*M列的矩阵，矩阵中的一个格子最多与四个格子相连（上、下、左、右）你每次可以给矩阵中一对相连的格子同时加上一个相同的整数，反复重复这个操作，你能得到一个全零的矩阵吗？<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为测试数据的组第一行为测试数据的组T；</p><p>对于每组测试数据的格式如下：</p><p>第一行为 N和 M；N表示矩阵的行数， M表示矩阵的列数； 中间用一个空格隔开</p><p>接下来N行，每行M个整数，第i行第j列的整数为a【i】【j】每两个整数之间用一个空格隔开<br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共 &nbsp;T行，对于每组数据如果这个矩阵经过反复操作能够得到一全零矩阵，输出 输出 &#39;Yes&#39;, 否则输出 &#39;No&#39; ，注意大小写， 不包含引号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>2 3</p><p>-1 1 100</p><p>-1 1 100</p><p>2 2</p><p>2 0</p><p>1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes<br></p><p>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 100%  的数据： 1≤T≤10 ；2≤N,M≤10 ；|A[i][j]|≤1,000 , 000；</p>
</div>
</div>