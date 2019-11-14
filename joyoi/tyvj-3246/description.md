# 

 
 # 题目描述 
<p>
击中目标（inside.pas/c/cpp）<br><br>【问题描述】<br><br>    现需要一个系统，对射击的准确率进行测试。一个射击者对一个目标发射n颗子弹，已知发射n颗子弹所击中的位置和目标所在位置，判断有多少颗子弹能打到目标内。目标是一个凸多边形区域，并且按顺时针或逆时针逐一给出顶点坐标，每一发子弹击中位置是一个坐标。规定子弹击中目标的边上或顶点也算打到目标内。请你编程实现这个系统。<br><br></p> 

 
 # 输入格式 
<p>
输入文件中包含以下内容，第一行为多边形顶点数n和发射子弹数目m；接下来n行为每个顶点坐标（按顺时针或逆时针顺序）；再接下来m行为每颗子弹所击中的位置坐标。</p> 

 
 # 输出格式 
<p>
 输出文件输出占一行，输出子弹击中目标的数目。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4 6
0 0
2 3
5 5
5 -1
5 3
7 3
5 -1
5 -2
2 3
4 1</td><td>4</td></tr></table>
