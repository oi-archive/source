<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>机器上有N个需要处理的任务，它们构成了一个序列。这些任务被标号为1到N，因此序列的排列为1,2,3...N。这N个任务被分成若干批，每批包含相邻的若干任务。从时刻0开始，这些任务被分批加工，第i个任务单独完成所需的时间是Ti。在每批任务开始前，机器需要启动时间S，而完成这批任务所需的时间是各个任务需要时间的总和。<strong>注意，同一批任务将在同一时刻完成。</strong>每个任务的费用是它的完成时刻乘以一个费用系数Fi。请确定一个分组方案，使得总费用最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数，N,S。</p>
<p>接下来N行每行两个整数，Ti,Fi。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">一个整数，为所求的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 1</p>
<p>1 3</p>
<p>3 2</p>
<p>4 3</p>
<p>2 3</p>
<p>1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>153</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="114">
<p>测试点</p>
</td>
<td valign="top" width="114">
<p>N</p>
</td>
<td valign="top" width="114">
<p>S</p>
</td>
<td valign="top" width="114">
<p>Ti</p>
</td>
<td valign="top" width="114">
<p>Fi</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[1, 4]</p>
</td>
<td valign="top" width="114">
<p>0&lt;N&lt;=1000</p>
</td>
<td valign="top" width="114">
<p> </p>
<p>0&lt;=S&lt;=2^8</p>
</td>
<td valign="top" width="114">
<p>0&lt;=Ti&lt;=2^8</p>
</td>
<td valign="top" width="114">
<p> </p>
<p>0&lt;=Fi&lt;=2^8</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[5, 12]</p>
</td>
<td valign="top" width="114">
<p>0&lt;N&lt;=300000</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[13, 20]</p>
</td>
<td valign="top" width="114">
<p>0&lt;N&lt;=100000</p>
</td>
<td valign="top" width="114">
<p>-(2^8)&lt;=Ti&lt;=2^8</p>
</td>
</tr>
</tbody>
</table>
</div>
</div>