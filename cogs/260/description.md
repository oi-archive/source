

# 问题描述

 
</h3>
    公元五八○一年，地球居民迁移至金牛座α第二行星，在那里发表银河联邦创立宣言，同年改元为宇宙历元年，并开始向银河系深处拓展。
</div>

# 输入格式



# 输出格式



# 样例输入


<pre>4
M 2 3
C 1 2
M 2 4
C 4 2
</pre>

# 样例说明


<div>
战舰位置图：表格中阿拉伯数字表示战舰编号
</div>
<table width="480" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<th width="80">
 
</th>
<th width="80">
第一列
</th>
<th width="80">
第二列
</th>
<th width="80">
第三列
</th>
<th width="80">
第四列
</th>
</tr>
<tr>
<td height="20" align="center">
初始时
</td>
<td align="center">
1
</td>
<td align="center">
2
</td>
<td align="center">
3
</td>
<td align="center">
4
</td>
<td align="center">
……
</td>
</tr>
<tr>
<td height="20" align="center">
M 2 3
</td>
<td align="center">
1
</td>
<td align="center">
3<br/>
2
</td>
<td align="center">
4
</td>
<td align="center">
……
</td>
</tr>
<tr>
<td height="20" align="center">
C 1 2
</td>
<td colspan="5" align="center">
1号战舰与2号战舰不在同一列，因此输出-1
</td>
</tr>
<tr>
<td height="20" align="center">
M 2 4
</td>
<td align="center">
1
</td>
<td align="center">
4<br/>
3<br/>
2
</td>
<td align="center">
……
</td>
</tr>
<tr>
<td height="20" align="center">
C 4 2
</td>
<td colspan="5" align="center">
4号战舰与2号战舰之间仅布置了一艘战舰，编号为3，输出1
</td>
</tr>
</tbody>
</table>
<p>
<br/>
</p>
