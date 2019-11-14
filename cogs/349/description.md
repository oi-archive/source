# 题目描述


<div>
【背景】
</div>
<div>
    小白(LWD)在一个由n条横街，m条纵街的地方逛街。现在他饿了，想去吃小吃。已知吃小吃在第n条横街上，且每个街区有ai家小吃.小白站在这个地方的左上角，为了早点吃小吃，他只向下和向右走。
</div>
<div>
【问题描述】
</div>
<div>
    在这n*m的地方，从左上角，只向下和向右走到第n行的某一段的ai中任意一点，求有多少种不同的方案。同一家店不同路线 和 同一路线不同店均视为不同的方案。
</div>
<div>
【输入文件】
</div>
<div>
第一行有二个整数n,m表示n行m列。<br/>
接下来m-1行，每行一个数ai表示第n行的每个街区的店数量。
</div>
<div>
【输出文件】
</div>
<div>
方案总数。
</div>
<div>
 
</div>
<div>
【输入样例】
</div>
<div align="left">
 
</div>
<div>
4 5<br/>
2<br/>
1<br/>
0<br/>
1
</div>
<div>
 
</div>
<div>
【输出样例】
</div>
<div>
26
</div>
<p>
小白
</p><table border="1" width="200">
<tbody>
<tr>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
</tr>
<tr>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
</tr>
<tr>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
</tr>
</tbody>
</table>
<p></p>
<p>
  2       1      0     1
</p>
<div>
26= 2*1 + 1*4 + 0*10 + 1*20
</div>
<div>
<strong>【数据范围】 </strong> 
</div>
<div>
对于 30%数据, 0&lt;=n,m&lt;=10;ai=1<br/>
对于100%数据, 0&lt;=n,m&lt;=1,000<br/>
对于 100%数据，0&lt;=ai&lt;=1000
</div>
