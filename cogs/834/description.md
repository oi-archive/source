

# 1,1000


<div>
 
</div>
<div>
</div>
<div>
格式
</div>
<div>
PROGRAM NAME: rect1
</div>
<div>
INPUT FORMAT:(file rect1.in)
</div>
<div>
</div>
<div>
每行输入的是放置长方形的方法。<br/>
第一行输入的是那个放在底的长方形(即白纸)。
<table border="1">
<tbody>
<tr>
<td>
第 1 行:
</td>
<td>
A ， B 和 N, 由空格分开 (1 &lt;=A, B&lt;=10,000)
</td>
</tr>
<tr>
<td>
第 2 到N+1行:
</td>
<td>
为五个整数　llx, lly, urx, ury, color　这是一个长方形的左下角坐标，右上角坐标和颜色。<br/>
颜色 1和底部白纸的颜色相同。
</td>
</tr>
</tbody>
</table>
 
</div>
<div>
OUTPUT FORMAT:(file rect1.out)
</div>
<div>
<p>
输出文件应该包含一个所有能被看到颜色连同该颜色的总面积的清单( 即使颜色的区域不是连续的)，按color的增序顺序。<br/>
不要显示没有区域的颜色。
</p>
</div>
<div>
SAMPLE INPUT
<div>
(file rect1.in)
</div>
</div>
<div>
20 20 3<br/>
2 2 18 18 2<br/>
0 8 19 19 3<br/>
8 0 10 19 4<br/>
</div>
<div>
SAMPLE OUTPUT
<div>
(file rect1.out)
</div>
</div>
<div>
1 91<br/>
2 84<br/>
3 187<br/>
4 38<br/>
 
</div>
</div>
</div>
</div>
</div>
