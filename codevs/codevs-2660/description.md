<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【问题描述】</p>
<p>Smart有一块100×100的矩形的土地，左下角的坐标为（0，0）右上角的坐标为（100，100）。他无聊的时候在里面种满了西瓜，但是总有人来偷，于是他买了两个侦察守卫。</p>
<p>一个侦察守卫的守卫范围是（x1，y1）到（x2，y2）的一块矩形范围，其中（x1，y1）代表左下角（x2，y2）代表右上角。</p>
<p>Smart认为被两个侦察守卫看护的区域是强安全区域，仅被一个侦察守卫看护的区域是弱安全区域，而没有被侦察守卫看护的区域是不安全区域。现在Smart想让你告诉他这三种区域的面积分别是多少。</p>
<p> </p>

<img src="/source/codevs/codevs-2660/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNjYwL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2ODgwMjkzMy42ODAuMzU5NzEwMzc0Mi5qcGc=.jpg" style="max-width:700px">

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
<p>输入有两行，每行四个整数x1，y1，x2，y2；分别表示两个侦查守卫的看护区域。</p>
<p>其中0≤x1&lt;x2，y1&lt;y2≤100，且两个矩形<strong>肯定有公共区域</strong>。</p>

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
<p>一行三个整数分别表示强安全区域，弱安全区域，不安全区域的面积。</p>
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
<p>【样例】</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="266">
<p>recon.in</p>
</td>
<td valign="top" width="274">
<p>recon.out</p>
</td>
</tr>
<tr>
<td valign="top" width="266">
<p>10 10 20 20</p>
<p>15 15 25 25</p>
</td>
<td valign="top" width="274">
<p>25 150 9825</p>
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
<p>【样例】</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="266">
<p>recon.in</p>
</td>
<td valign="top" width="274">
<p>recon.out</p>
</td>
</tr>
<tr>
<td valign="top" width="266">
<p>10 10 20 20</p>
<p>15 15 25 25</p>
</td>
<td valign="top" width="274">
<p>25 150 9825</p>
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
<p>0≤x1&lt;x2，y1&lt;y2≤100</p>
</div>
</div>