<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这是一个很古老的游戏了：有一个3 × 3的活动拼盘（如下图），方格上写有0~8这九个数字。例如：</p>
<p> </p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top">
<p>3</p>
</td>
<td valign="top">
<p>7</p>
</td>
<td valign="top">
<p>5</p>
</td>
</tr>
<tr>
<td valign="top">
<p>2</p>
</td>
<td valign="top">
<p>6</p>
</td>
<td valign="top">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top">
<p>4</p>
</td>
<td valign="top">
<p>8</p>
</td>
<td valign="top">
<p>0</p>
</td>
</tr>
</tbody>
</table>
</div>
<p> </p>
<p>利用拼盘背后的旋钮，游戏者每次可以进行以下两种操作之一：</p>
<p>1．将拼盘外围的8个方格按顺时针挪一个位置。</p>
<p>2．将中间一行向右移动一个位置，最右边的方格被移到最左边。</p>
<p> </p>
<p> </p>
<p>给你一个拼盘的初始状态，你能用最少的操作次数把拼盘变成下图所示的目标状态吗？</p>
<p> </p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top">
<p>0</p>
</td>
<td valign="top">
<p>1</p>
</td>
<td valign="top">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top">
<p>3</p>
</td>
<td valign="top">
<p>4</p>
</td>
<td valign="top">
<p>5</p>
</td>
</tr>
<tr>
<td valign="top">
<p>6</p>
</td>
<td valign="top">
<p>7</p>
</td>
<td valign="top">
<p>8</p>
</td>
</tr>
</tbody>
</table>
</div>
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
<p>输入文件中包含三行三列九个数，同行的相邻两数用空格隔开，表示初始状态每个方格上的数字。初始状态不会是目标状态。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果目标状态无法达到，则输出&ldquo;UNSOLVABLE&rdquo;（引号不输出）。</p>
<p>否则，第一行是一个整数S，表示最少的操作次数。接下来4 &times; (S + 1)行，每四行表示一个状态：前三行每行三个整数，相邻两数用空格隔开，表示每个方格上的数字，第四行是一个空行，作为分隔。第一个状态必须是初始状态，最后一个状态必须是目标状态。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3 0</p>
<p>1 8 7</p>
<p>5 4 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>2 3 0</p>
<p>1 8 7</p>
<p>5 4 6</p>
<p> </p>
<p>1 2 3</p>
<p>5 8 0</p>
<p>4 6 7</p>
<p> </p>
<p>1 2 3</p>
<p>0 5 8</p>
<p>4 6 7</p>
<p> </p>
<p>0 1 2</p>
<p>4 5 3</p>
<p>6 7 8</p>
<p> </p>
<p>0 1 2</p>
<p>3 4 5</p>
<p>6 7 8</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>