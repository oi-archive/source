<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>传说很遥远的藏宝楼顶层藏着诱人的宝藏。小明历尽千辛万苦终于</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>找到传说中的这个藏宝楼，藏宝楼的门口竖着一个木板，上面写有几</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>个大字，寻宝说明书。说明书的内容如下：</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>藏宝楼共有 N+1 层，最上面一层是顶层，顶层有一个房间里面藏</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>着宝藏，每一层有 M 个房间。一开始，你可以从第一层的任何一个</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>房间进入，每个房间都有一个木牌，上面有一个数字，你可以顺时针</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>或逆时针走，你每进入一个房间，就将房间内的数字进行累加，宝箱</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>的密码就是到顶层可以得到的最小值。</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>请帮助小明算出这个打开宝箱的密钥。</p>
</td>
</tr>
</tbody>
</table>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>第一行 2 个整数 N 和 M，之间用一个空格隔开。N 表示除了顶层</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>外藏宝楼共 N 层楼，M 表示除顶层外每层楼有 M 个房间。</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>接下来 N*M 行，每行两个整数之间用一个空格隔开，每行描述一</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>个房间内的情况</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>其中第(i-1)*M+j 行表示第 i 层 j-1 号房间的情况</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>(i=1, 2, …,N j=1, 2,… ,M)。</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>第一个整数表示该房间是否有楼梯通往上一层，0 表示没有，1 表</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>示有，第二个整数表示指示牌上的数字。注意，从 j 号房间的楼梯爬</p>
</td>
</tr>
</tbody>
</table>
</div>
<p>到上一层到达的房间一定也是 j 号房间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<div>
<table style="width: 583px;" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td align="left" valign="top">
<p align="left">输出只有一行，一个整数，表示打开宝箱的密钥，若无可通往顶层</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table style="width: 175px;" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td align="left" valign="top">
<p align="left">的路，输出-1。</p>
</td>
</tr>
</tbody>
</table>
</div>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>12</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>1 1000</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>01</p>
</td>
</tr>
</tbody>
</table>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p>对于 50%的数据，N≤20 M≤20</p>
</td>
</tr>
</tbody>
</table>
</div>
<div>
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<p> 对于100%的数据，N≤60 M≤60</p>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>