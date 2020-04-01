<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在给你一个N*N的矩阵，每个位置上都有一个数，初始为0，现在需要支持三种操作：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="189">
<p>命令</p>
</td>
<td valign="top" width="189">
<p>参数限制</p>
</td>
<td valign="top" width="189">
<p>内容</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>1 x y A</p>
</td>
<td valign="top" width="189">
<p>1&lt;=x,y&lt;=N，A是正整数</p>
</td>
<td valign="top" width="189">
<p>将格子x,y里的数字加上A</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>2 x<sub>1</sub> y<sub>1</sub> x<sub>2</sub> y<sub>2</sub></p>
</td>
<td valign="top" width="189">
<p>1&lt;=x<sub>1</sub>&lt;= x<sub>2</sub>&lt;=N</p>
<p>1&lt;=y<sub>1</sub>&lt;= y<sub>2</sub>&lt;=N</p>
</td>
<td valign="top" width="189">
<p>输出x<sub>1</sub> y<sub>1</sub> x<sub>2</sub> y<sub>2</sub>这个矩形内的数字和</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>3</p>
</td>
<td valign="top" width="189">
<p>无</p>
</td>
<td valign="top" width="189">
<p>终止程序</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行一个正整数N。</p>
<p>接下来每行一个操作。</p>
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

<p>对于每个2操作，输出一个对应的答案。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br> 1 2 3 3<br> 2 1 1 3 3<br> 1 2 2 2<br> 2 2 2 3 4<br> 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br> 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>测试点分布如下：<br> 1，2    1&lt;=N&lt;=100,操作数不超过100个，内存限制512M。 <br> 3，4    1&lt;=N&lt;=1000,操作数不超过100000个，内存限制512M。 <br> 5，6    1&lt;=N&lt;=200000,操作数不超过100000个，内存限制512M。 <br> 7-10    1&lt;=N&lt;=500000,操作数不超过200000个，内存限制20M。</p>
</div>
</div>