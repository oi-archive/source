<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一棵树<span style="">，求出最小的</span><span style="font-family: Times New Roman;">k</span><span style="">，使得</span>，且在<span style="font-family: Times New Roman;">树</span><span style="">中存在路径</span><span style="">P，使得k&gt;= S 且 k &lt;=E. （k为路径P上的边的权值和）<br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行给出N，S，E，N代表树的点数，S，E如题目描述一致</p>
<p>下面N-1行给出这棵树的相邻两个节点的边及其权值W</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数k，表示存在路径P,并且路径上的权值和 K&gt;=S , k&lt;=E，若无解输出-1</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5 10 40</span></p>
<p><span>2 4 80</span></p>
<p><span>2 3 57</span></p>
<p><span>1 2 16</span></p>
<p><span>2 5 49<br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>16<br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>边权W&lt;=10000,</p>
<p>保证答案在int（longint）范围内,且|E-S|&lt;=50，</p>
<p>树上点的个数N&lt;=30000</p>
</div>
</div>