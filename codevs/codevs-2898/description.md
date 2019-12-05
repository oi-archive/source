<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>著名科学家卢斯为了检查学生对进位制的理解，他给出了如下的一张加法表，表中的字母代表数字。 例如下图：                                                    </p>
<p>其含义为：</p>
<p>L+L=L<span style="">，</span><span style="font-family: 'Times New Roman';">L+K=K</span><span style="">，</span><span style="font-family: 'Times New Roman';">L+V=V</span><span style="">，</span><span style="font-family: 'Times New Roman';">L+E=E</span></p>
<p>K+L=K<span style="">，</span><span style="font-family: 'Times New Roman';">K+K=V</span><span style="">，</span><span style="font-family: 'Times New Roman';">K+V=E</span><span style="">，</span><span style="font-family: 'Times New Roman';">K+E=KL</span>         ……</p>
<p>E+E=KV</p>
<table border="1">
<tbody>
<tr>
<td>+</td>
<td>L</td>
<td>K</td>
<td>V</td>
<td>E</td>
</tr>
<tr>
<td>L</td>
<td>L</td>
<td>K</td>
<td>V</td>
<td>E</td>
</tr>
<tr>
<td>K</td>
<td>K</td>
<td>V</td>
<td>E</td>
<td>KL</td>
</tr>
<tr>
<td>V</td>
<td>V</td>
<td>E</td>
<td>KL</td>
<td>KK</td>
</tr>
<tr>
<td>E</td>
<td>E</td>
<td>KL</td>
<td>KK</td>
<td>KV</td>
</tr>
</tbody>
</table>
<p> </p>
<p> </p>
<p>    根据这些规则可推导出：<span style="font-family: 'Times New Roman';">L=0</span><span style="">，</span><span style="font-family: 'Times New Roman';">K=1</span><span style="">，</span><span style="font-family: 'Times New Roman';">V=2</span><span style="">，</span><span style="font-family: 'Times New Roman';">E=3</span></p>
<p>                          同时可以确定该表表示的是<span style="font-family: 'Times New Roman';">4</span><span style="">进制加法</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>程序输入：</p>
<p> n<span style="">（</span>n≤<span style="font-family: 'Times New Roman';">9</span><span style="">）表示行数。</span></p>
<p>以下<span style="font-family: 'Times New Roman';">n</span><span style="">行，每行包括</span>n个字符串，每个字串间用空格隔开。（字串仅有一个为‘<span style="font-family: 'Times New Roman';">+</span><span style="">’号，其它都由大写字母组成）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<div class="Section0">
<p class="p0">程序输出：</p>
<p class="p0">①&nbsp;各个字母表示什么数，格式如：<span style="font-family: 'Times New Roman';">L=0</span><span style="font-family: 宋体;">，</span><span style="font-family: 'Times New Roman';">K=1</span><span style="font-family: 宋体;">，&hellip;&hellip;</span></p>
<p class="p0">②&nbsp;加法运算是几进制的。</p>
<p class="p0">③&nbsp;若不可能组成加法表，则应输出&ldquo;<span style="font-family: 'Times New Roman';">ERROR!</span><span style="font-family: 宋体;">&rdquo;</span></p>
<p class="p0">&nbsp;</p>
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
<p>4<br>+ M N P<br>M N MP M<br>N MP MN N<br>P M N P</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>M=1 N=2 P=0<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>范围极小，NOIP1998原题，数据都没改</p>
</div>
</div>