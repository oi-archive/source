<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">给出 <span style="font-family: 'Times New Roman';">N</span>，<span style="font-family: 'Times New Roman';">B </span>和 <span style="font-family: 'Times New Roman';">D</span>：找出 <span style="font-family: 'Times New Roman';">N </span>个编码（<span style="font-family: 'Times New Roman';">1 &lt;= N &lt;= 64</span>），每个编码有 <span style="font-family: 'Times New Roman';">B </span>位（<span style="font-family: 'Times New Roman';">1 &lt;= B &lt;= 8</span>），使得两两编码之间至少有 <span style="font-family: 'Times New Roman';">D </span>个单位的<span style="font-family: 'Times New Roman';">“</span>海明距离<span style="font-family: 'Times New Roman';">”</span>（<span style="font-family: 'Times New Roman';">1 &lt;= D &lt;= 7</span>）。<span style="font-family: 'Times New Roman';">“</span>海明距离<span style="font-family: 'Times New Roman';">”</span>是指对于两个编码，他们的二进制表示法中的不同二进制位的数目。看下面的两个编码 <span style="font-family: 'Times New Roman';">0x554 </span>和 <span style="font-family: 'Times New Roman';">0x234 </span>之间的区别（<span style="font-family: 'Times New Roman';">0x554 </span>表示一个十六进制数，每个位上分别是 <span style="font-family: 'Times New Roman';">5</span>，<span style="font-family: 'Times New Roman';">5</span>，<span style="font-family: 'Times New Roman';">4</span>）： <!--mstheme--></span></p>
<pre>        <span style="font-family: 'Times New Roman';">0x554 = 0101 0101 0100 0x234 = 0010 0011 0100 </span>不同的二进制位<span style="font-family: 'Times New Roman';">: xxx xx </span></pre>
<p>因为有五个位不同，所以<span style="font-family: 'Times New Roman';">“</span>海明距离<span style="font-family: 'Times New Roman';">”</span>是 <span style="font-family: 'Times New Roman';">5</span>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行，包括 <span style="font-family: 'Times New Roman';">N, B, D</span>。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Times New Roman';">N 个编码（用十进制表示），要排序，十个一行。如果有多解，你的程序要输出这样的解：假如把它化为 2^B 进制的数，它的值要最小。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre><span style="font-family: 'Times New Roman';">16 7 3 </span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p></p>
<table border="0" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top">
<table style="">
<tbody>
<tr>
<td>
<pre><span style="font-family: 'Times New Roman';">0 7 25 30 42 45 51 52 75 76 82 85 97 102 120 127</span></pre>
<!--mstheme--></td>
</tr>
</tbody>
</table>
<!--mstheme--><span style=""><span style="font-family: 'Times New Roman';"><br></span><!--mstheme--></span><!--msnavigation--></td>
</tr>
<!--msnavigation--></tbody>
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

</div>
</div>