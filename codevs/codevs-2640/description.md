<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<h2>打印页数</h2>
<p>【问题描述】</p>
<p>Smart从保密局那里得到了一些关于NOIP2012的情报，他想在NOIP复赛前把整理的资料打印出来，仔细研究：这份资料的正文包含许多行，某些行可能包含一些脚注标记，一个脚注可能包含一行或多行，并且必须和对应的脚注标记印刷在<strong>同一页</strong>。</p>
<p>一页所允许印刷的最多行数是已知的，任何一页都不允许超过该行数(包括脚注)，但是Smart的纸不多了，他只好尽可能的少用纸，他想知道这份资料最少要用多少页打印出来。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>【输入格式】</p>
<p>第一行包含两个整数：资料正文的总行数N（2≤N≤1000）和打印每一页所能包含的最多行数K（2≤K≤1000）；</p>
<p>第二行包含一个整数F（1≤F≤100），表示该资料所包含的脚注总数。</p>
<p>接下来的F行每行包含两个用空格隔开的整数X和Y，表示正文的第X行包含一个脚注标记，该脚注标记对应的脚注需要Y行，脚注将按它们在文件中被引用的先后排序。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>【输出格式】</p>
<p>仅一行，一个整数，表示打印该资料所需的最少页数。</p>
<p>&nbsp;&nbsp;&nbsp; （保证有解）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="298">
<p>7 3</p>
<p>2</p>
<p>2 1</p>
<p>4 2</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="297">
<p>4</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数：资料正文的总行数N（2≤N≤1000）和打印每一页所能包含的最多行数K（2≤K≤1000）；</p>
<p>第二行包含一个整数F（1≤F≤100），表示该资料所包含的脚注总数。</p>
</div>
</div>