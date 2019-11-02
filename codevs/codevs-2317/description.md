<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个N*M个方格组成的棋盘内，有K个方格被称为特殊方格。我们要使用一组俄罗斯方块来覆盖这个棋盘，保证特殊方格不能被覆盖，非特殊方格只能被一个俄罗斯方块覆盖，求最多能容纳的俄罗斯方块的数量。</p>
<p>已知有以下三组俄罗斯方块，一个棋盘可能用其中的某一组。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个整数，N,M,K，和一个字符，type，为所用的俄罗斯方块组。</p>
<p>接下来K行每行两个整数，X,Y，表示第X行第Y列为特殊方格。</p>

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
<p>7 6 6 C</p>
<p>3 1</p>
<p>3 6</p>
<p>5 3</p>
<p>5 4</p>
<p>5 7</p>
<p>6 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

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
<td valign="top" width="192">
<p>N,M</p>
</td>
<td valign="top" width="225">
<p>K</p>
</td>
<td valign="top" width="63">
<p>type</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[1, 6]</p>
</td>
<td valign="top" width="192">
<p>0 &lt; N,M &lt;= 100</p>
</td>
<td valign="top" width="225">
<p>0&lt;=K&lt;=N*M</p>
</td>
<td valign="top" width="63">
<p>A</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[7, 12]</p>
</td>
<td valign="top" width="192">
<p>N=M=2^L,0&lt;L&lt;=200000</p>
</td>
<td valign="top" width="225">
<p>K=1</p>
</td>
<td valign="top" width="63">
<p>B</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[13, 20]</p>
</td>
<td valign="top" width="192">
<p>0&lt;N,M&lt;=11</p>
</td>
<td valign="top" width="225">
<p>0&lt;=K&lt;=N*M</p>
</td>
<td valign="top" width="63">
<p>C</p>
</td>
</tr>
</tbody>
</table>
</div>
</div>