<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【问题描述】</p>
<p>Smart发现一个了宝藏，他来到了宝藏所在的的洞穴想进去挖宝藏，可是洞穴门口却有着险恶的机关。门上有着N个宝珠，每个宝珠都有一个数字。传说，只要宝珠里的两颗珠撞在一起后就会发出奇异的光彩，但发出的光彩有可能是致命的，也有可能是打开前进之路的钥匙。Smart询问老者后，得知要想打开这扇门，就得找出两颗珠宝，使这两颗珠宝撞在一起后产生的能量值最接近123。</p>
<p>两颗珠宝撞在一起以后产生的能量值的计算方法是：将两个珠宝所代表的数字转换为7进制的数后，一一对照这两个七进制数的每一位，若相同，则结果为0否则为1。</p>
<p>例如：两颗珠子所代表的数为18和370，将这两个数转化为7进制后是24和1036，对于高位不足的数，采取高位添‘0'的方法，即两个数为0024，1036。最后得到的能量值C为1011，再将C当作二进制数转换为十进制数。那么转换后的C就为这两个珠撞在一起以后所产生的能量值。</p>

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
<p>第一行一个整数N，表示宝珠的数量。（2≤N≤1000）</p>
<p>第二行N个数，每个数用空格隔开，每个数表示第i个宝珠所代表的数字(0≤每个数≤11111)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出格式】</p>
<p>一个数，代表你所找到的最接近123的能量值。</p>

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
<p>jewelry.in</p>
</td>
<td valign="top" width="274">
<p>jewelry.out</p>
</td>
</tr>
<tr>
<td valign="top" width="266">
<p>5</p>
<p>18 370 45 36 78</p>
</td>
<td valign="top" width="274">
<p>15</p>
</td>
</tr>
</tbody>
</table>
<p>【样例说明】</p>
<p>370和78这两颗宝珠所产生的能量值15最接近123。</p>

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
<p>【样例】</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="266">
<p>jewelry.in</p>
</td>
<td valign="top" width="274">
<p>jewelry.out</p>
</td>
</tr>
<tr>
<td valign="top" width="266">
<p>5</p>
<p>18 370 45 36 78</p>
</td>
<td valign="top" width="274">
<p>15</p>
</td>
</tr>
</tbody>
</table>
<p>【样例说明】</p>
<p>370和78这两颗宝珠所产生的能量值15最接近123。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（2≤N≤1000）</p>
<p>(0≤每个数≤11111)。</p>
</div>
</div>