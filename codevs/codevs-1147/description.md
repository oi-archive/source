<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>上课的时候总有一些同学和前后左右的人交头接耳，这是令小学班主任十分头疼的一件事情。不过，班主任小雪发现了一些有趣的现象，当同学们的座次确定下来之后，只有有限的D对同学上课时会交头接耳。同学们在教室中坐成了M行N列，坐在第i行第j列的同学的位置是（i，j），为了方便同学们进出，在教室中设置了K条横向的通道，L条纵向的通道。于是，聪明的小雪想到了一个办法，或许可以减少上课时学生交头接耳的问题：她打算重新摆放桌椅，改变同学们桌椅间通道的位置，因为如果一条通道隔开了两个会交头接耳的同学，那么他们就不会交头接耳了。</p>
<p>请你帮忙给小雪编写一个程序，给出最好的通道划分方案。在该方案下，上课时交头接耳的学生对数最少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，有5各用空格隔开的整数，分别是M，N，K，L，D（2&lt;=N，M&lt;=1000，0&lt;=K&lt;M，0&lt;=L&lt;N，D&lt;=2000）。</p>
<p>接下来D行，每行有4个用空格隔开的整数，第i行的4个整数X<sub>i</sub>，Y<sub>i</sub>，P<sub>i</sub>，Q<sub>i</sub>，表示坐在位置(X<sub>i</sub>,Y<sub>i</sub>)与(P<sub>i</sub>,Q<sub>i</sub>)的两个同学会交头接耳（输入保证他们前后相邻或者左右相邻）。</p>
<p>输入数据保证最优方案的唯一性。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共两行。</p>
<p>第一行包含K个整数，a<sub>1</sub>a<sub>2</sub>&hellip;&hellip;a<sub>K</sub>，表示第a<sub>1</sub>行和a<sub>1</sub>+1行之间、第a<sub>2</sub>行和第a<sub>2</sub>+1行之间、&hellip;、第a<sub>K</sub>行和第a<sub>K</sub>+1行之间要开辟通道，其中a<sub>i</sub>&lt; a<sub>i+1</sub>，每两个整数之间用空格隔开（行尾没有空格）。</p>
<p>第二行包含L个整数，b<sub>1</sub>b<sub>2</sub>&hellip;&hellip;b<sub>k</sub>，表示第b<sub>1</sub>列和b<sub>1</sub>+1列之间、第b<sub>2</sub>列和第b<sub>2</sub>+1列之间、&hellip;、第b<sub>L</sub>列和第b<sub>L</sub>+1列之间要开辟通道，其中b<sub>i</sub>&lt; b<sub>i+1</sub>，每两个整数之间用空格隔开（行尾没有空格）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 1 2 3</p>
<p>4 2 4 3</p>
<p>2 3 3 3</p>
<p>2 5 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> </p>
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="0" width="104"> </td>
<td width="9"> </td>
<td width="89"> </td>
<td width="9"> </td>
</tr>
<tr>
<td height="241"> </td>
<td valign="top"> </td>
<td> </td>
<td valign="top"> </td>
</tr>
</tbody>
</table>
<p>&lt;!--[endif]--&gt;<span style=""> </span></p>
<p><span style=""> </span></p>
<p> </p>
<table border="1" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr style="">
<td style="" width="48">
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="42" style="" width="39">&lt;!--[endif]--&gt;&lt;!--[if !mso]--&gt;
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td>&lt;!--[endif]--&gt;
<div style="">
<p><span>3 &lt;!--[if !vml]--&gt;&lt;!--[endif]--&gt;</span></p>
</div>
&lt;!--[if !mso]--&gt;</td>
</tr>
</tbody>
</table>
&lt;!--[endif]--&gt;&lt;!--[if !mso &amp; !vml]--&gt; &lt;!--[endif]--&gt;&lt;!--[if !vml]--&gt;</td>
</tr>
</tbody>
</table>
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="42" style="" width="39">&lt;!--[endif]--&gt;&lt;!--[if !mso]--&gt;
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td>&lt;!--[endif]--&gt;
<div style="">
<p><span>4</span></p>
</div>
&lt;!--[if !mso]--&gt;</td>
</tr>
</tbody>
</table>
&lt;!--[endif]--&gt;&lt;!--[if !mso &amp; !vml]--&gt; &lt;!--[endif]--&gt;&lt;!--[if !vml]--&gt;</td>
</tr>
</tbody>
</table>
</td>
<td style="" width="48">
<p style=""><span>*</span></p>
</td>
<td style="" width="48">
<p style=""><span>*</span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
</tr>
<tr style="">
<td style="" width="48"> </td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
<td style="" width="48">
<p style=""><span style="">※</span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
</tr>
<tr style="">
<td style="" width="48">
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="42" style="" width="39">&lt;!--[endif]--&gt;&lt;!--[if !mso]--&gt;
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td>&lt;!--[endif]--&gt;
<div style="">
<p><span>2</span></p>
</div>
&lt;!--[if !mso]--&gt;</td>
</tr>
</tbody>
</table>
&lt;!--[endif]--&gt;&lt;!--[if !mso &amp; !vml]--&gt; &lt;!--[endif]--&gt;&lt;!--[if !vml]--&gt;</td>
</tr>
</tbody>
</table>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
<p style=""><span style="">※</span></p>
</td>
<td style="" width="48">
<p style=""><span>+</span></p>
</td>
<td style="" width="48">
<p style=""><span>+</span></p>
</td>
</tr>
<tr style="">
<td style="" width="48">
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="32" style="" width="39">&lt;!--[endif]--&gt;&lt;!--[if !mso]--&gt;
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td>&lt;!--[endif]--&gt;
<div style="">
<p><span>1</span></p>
</div>
&lt;!--[if !mso]--&gt;</td>
</tr>
</tbody>
</table>
&lt;!--[endif]--&gt;&lt;!--[if !mso &amp; !vml]--&gt; &lt;!--[endif]--&gt;&lt;!--[if !vml]--&gt;</td>
</tr>
</tbody>
</table>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
<td style="" width="48">
<p style=""><span> </span></p>
</td>
</tr>
</tbody>
</table>
<p style=""><span>1       2     3      4      5</span></p>
<p><span> </span></p>
</div>
</div>