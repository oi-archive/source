<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在一个R行C列的表格里，我们要选出3个不同的单元格。但要满足如下的两个条件：</span></p><p style=""><span style="">（1）选中的任意两个单元格都不在同一行。</span></p><p style=""><span style="">（2）选中的任意两个单元格都不在同一列。</span></p><p style=""><span style="">假设我们选中的单元格分别是：A，B，C，那么我们定义这种选择的<strong>“费用”</strong>= f[A][B] + f[B][C] + f[C][A]。 其中f[A][B]是指单元格A到单元格B的距离，即两个单元格所在行编号的差的绝对值 + 两个单元格所在列编号的差的绝对值。例如：单元格A在第3行第2列，单元格B在第5行第1列，那么f[A][B] = <strong>|</strong>3-5<strong>|</strong> +<strong> |</strong>2-1<strong>| = 2 + 1 = 3</strong>。至于f[B][C], f[C][A]的意义也是同样的道理。现在你的任务是：有多少种不同的选择方案，使得<strong>“费用”</strong>不小于给定的数minT，而且不大于给定的数maxT，即<strong>“费用”</strong>在【minT, maxT】范围内有多少种不同的选择方案。答案模1000000007。所谓的两种不同方案是指：只要它们选中的单元格有一个不同，就认为是不同的方案。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">一行，4个整数，R、C、minT、maxT。3</span><span style="">≤</span><span style="">R,C</span><span style="">≤</span><span style="">4000, 1</span><span style="">≤</span><span style="">minT</span><span style="">≤</span><span style="">maxT</span><span style="">≤</span><span style="">20000</span><span style="">。</span></p><p style=""><strong><span style="">对于30%的<span style="">数据</span>,  3 </span></strong><span style="">≤</span><strong><span style=""> R, C </span></strong><span style="">≤</span><strong><span style=""> 70。</span></strong></p><p><strong><span style=""><br></span></strong></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:16px;font-family:宋体">一个整数，表示不同的选择方案数量模1000000007后的结果。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">3 3 1 20000</span></p><p><span style=""><br></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">6</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">3</span><span style="">≤</span><span style="">R,C</span><span style="">≤</span><span style="">4000, 1</span><span style="">≤</span><span style="">minT</span><span style="">≤</span><span style="">maxT</span><span style="">≤</span><span style="">20000</span><span style="">。</span></p>
</div>
</div>