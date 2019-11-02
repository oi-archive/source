<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>佳佳和明明玩一个猜数游戏。佳佳想一个1~<em>n</em>之间的整数，明明每次可以随便猜一个数。从第二次猜测起，佳佳告诉明明本次猜测的数和上次猜测的数相比哪个更接近。B表示本次猜测的数更接近，W表示上次猜测的数更接近。如果两次猜测的接近程度一样，则既可回答B也可回答W。</p>
<p>比如佳佳想的是10，下面是一个可能的猜测过程：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="95">
<p>猜测</p>
</td>
<td valign="top" width="95">
<p>5</p>
</td>
<td valign="top" width="95">
<p>8</p>
</td>
<td valign="top" width="95">
<p>11</p>
</td>
<td valign="top" width="95">
<p>6</p>
</td>
<td valign="top" width="95">
<p>14</p>
</td>
</tr>
<tr>
<td valign="top" width="95">
<p>距离</p>
</td>
<td valign="top" width="95">
<p>5</p>
</td>
<td valign="top" width="95">
<p>2</p>
</td>
<td valign="top" width="95">
<p>1</p>
</td>
<td valign="top" width="95">
<p>4</p>
</td>
<td valign="top" width="95">
<p>4</p>
</td>
</tr>
<tr>
<td valign="top" width="95">
<p>回答</p>
</td>
<td valign="top" width="95">
<p> </p>
</td>
<td valign="top" width="95">
<p>B</p>
</td>
<td valign="top" width="95">
<p>B</p>
</td>
<td valign="top" width="95">
<p>W</p>
</td>
<td valign="top" width="95">
<p>B/W</p>
</td>
</tr>
</tbody>
</table>
<p>明明只知道n，但是它并不知道佳佳想的是什么数。如果明明足够聪明，需要猜多少次才能保证猜到呢？</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>包含一个整数n，表示佳佳所想数的最大值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含一个整数k，表示最坏情况需要猜的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>75</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：1&lt;=<em>n</em>&lt;=20</p>
<p>100%的数据满足：1&lt;=<em>n</em>&lt;=300</p>
</div>
</div>