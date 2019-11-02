# 

 
 # 题目描述 
<p>
线段相交（linecross.pas/c/cpp）<br><br>【问题描述】<br><br>　 　 基本问题:判断二维平面上的两条线段是否相交。<br>　 　 注意：相交有很多种，这里指的“相交”是指两条线段恰好有唯一一个不是端点的公共点，我们称为“规范相交”。即如果一条线段的一个端点恰在另一线段上，则不视为相交；如果两条线段部分重合，也不视为相交，（这些情况我们称为“非规范相交”）<br><br><br><center><img src="/source/joyoi/tyvj-3242/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI0Mi9wcm9ibGVtc19pbWFnZXMvMTgwMS9wMS5naWY=.gif"></img></center></p> 

 
 # 输入格式 
<p>
输入共两行，每行四个实数，分别表示一条线段的两个端点：(x1,y1),(x2,y2)</p> 

 
 # 输出格式 
<p>
如果规范相交，则输出“YES”<br>否则，输出“NO”</p> 
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
<tr><td>4 8 11 14
9 3 5 23</td><td>YES</td></tr></table>
