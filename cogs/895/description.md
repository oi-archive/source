# 题目描述


<div>
USACO/frameup(译by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
<p>
看下面的五张 <span style="font-family:&#39;Times New Roman&#39;;">9 x 8 </span>的图像：
</p>
<pre><span style="font-family:宋体;">........   ........   ........   ........   .CCC....
EEEEEE..   ........   ........   ..BBBB..   .C.C....
E....E..   DDDDDD..   ........   ..B..B..   .C.C....
E....E..   D....D..   ........   ..B..B..   .CCC....
E....E..   D....D..   ....AAAA   ..B..B..   ........
E....E..   D....D..   ....A..A   ..BBBB..   ........
E....E..   DDDDDD..   ....A..A   ........   ........
E....E..   ........   ....AAAA   ........   ........
EEEEEE..   ........   ........   ........   ........

   1          2           3          4          5</span><span style="font-family:&#39;Times New Roman&#39;;"> </span></pre>
<p>
现在，把这些图像按照 <span style="font-family:&#39;Times New Roman&#39;;">1—5 </span>的编号从下到上重叠，第 <span style="font-family:&#39;Times New Roman&#39;;">1 </span>张在最下面，第 <span style="font-family:&#39;Times New Roman&#39;;">5 </span>张在最顶端。如果一张图像覆盖了另外一张图像，那么底下的图像的一部分就变得不可见了。我们得到下面的图像：
</p>
<pre><span style="font-family:宋体;"> .CCC....
 ECBCBB..
 DCBCDB..
 DCCC.B..
 D.B.ABAA
 D.BBBB.A
 DDDDAD.A
 E...AAAA
 EEEEEE..</span><span style="font-family:&#39;Times New Roman&#39;;"> </span></pre>
<p>
对于这样一张图像，计算构成这张图像的矩形图像从底部到顶端堆叠的顺序。
</p>
<p>
下面是这道题目的规则：
</p>
<ul>
<li>
矩形的边的宽度为 <span style="font-family:&#39;Times New Roman&#39;;">1 </span>，每条边的长度都不小于 <span style="font-family:&#39;Times New Roman&#39;;">3 </span>。
</li>
<li>
矩形的每条边中，至少有一部分是可见的。注意，一个角同时属于两条边。
</li>
<li>
矩形用大写字母表示，并且每个矩形的表示符号都不相同。
</li>
</ul>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: frameup</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file frameup.in)</span> 
</h3>
<table border="1">
<tbody>
<tr>
<td width="165">
<div align="center">
第一行
</div>
</td>
<td width="789">
<p>
两个用空格分开的整数：图像高 <span style="font-family:&#39;Times New Roman&#39;;">H (3 &lt;= H &lt;=30) </span>和图像宽 <span style="font-family:&#39;Times New Roman&#39;;">W (3 &lt;= W &lt;= 30) </span>。
</p>
</td>
</tr>
<tr>
<td>
<div align="center">
第二行到第 <span style="font-family:&#39;Times New Roman&#39;;">H+1 </span>行
</div>
</td>
<td>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">H </span>行，每行 <span style="font-family:&#39;Times New Roman&#39;;">W </span>个字母。
</p>
</td>
</tr>
</tbody>
</table>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file frameup.out)</span> 
</h3>
</span> 
</h3>
<p>
按照自底向上的顺序输出字母。如果有不止一种情况，按照字典顺序输出每一种情况（至少会有一种合法的顺序）。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file frameup.in)</span> 
</h3>
<pre><span style="font-family:宋体;">9 8
.CCC....
ECBCBB..
DCBCDB..
DCCC.B..
D.B.ABAA
D.BBBB.A
DDDDAD.A
E...AAAA
EEEEEE..</span><span style="font-family:&#39;Times New Roman&#39;;"> </span></pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file frameup.out)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">EDABC</span></pre>
<p>
 
</p>
