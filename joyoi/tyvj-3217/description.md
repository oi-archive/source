# 

 
 # 题目描述 
<p>
最长k可重线段集问题（line.cpp/c/pas）<br><br>【问题描述】<br><br>　　给定平面xoy 上n 个开线段组成的集合I，和一个正整数k，试设计一个算法，从开线段集合I 中选取出开线段集合S<img src="/source/joyoi/tyvj-3217/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxNy9wcm9ibGVtc19pbWFnZXMvMTYyNS9wMS5naWY=.gif"></img>I，使得在x 轴上的任何一点p，S 中与直线x=p 相交的开线段个数不超过k，且<img src="/source/joyoi/tyvj-3217/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxNy9wcm9ibGVtc19pbWFnZXMvMTYyNS9wMi5naWY=.gif"></img>达到最大。这样的集合S称为开线段集合I的最长k可重线段集。  称为最长k可重线段集的长度。对于任何开线段z，设其端点坐标为（ x0 , y0 ）<br>和（ x1 , y1 ），则开线段z 的长度|z|定义为：<img src="/source/joyoi/tyvj-3217/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxNy9wcm9ibGVtc19pbWFnZXMvMTYyNS9wMy5naWY=.gif"></img><br><br>【编程任务】<br><br>　　对于给定的开线段集合I和正整数k，计算开线段集合I的最长k可重线段集的长度。</p> 

 
 # 输入格式 
<p>
由文件line.in提供输入数据。<br><br>文件的第1 行有2 个正整数n和k，分别表示开线段的个数和开线段的可重迭数。接下来的n行，每行有4个整数，表示开线段的2 个端点坐标。</p> 

 
 # 输出格式 
<p>
程序运行结束时，将计算出的最长k可重线段集的长度输出到文件line.out中。</p> 
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
<tr><td>4 2
1 2 7 3
6 5 8 3
7 8 10 5
9 6 13 9</td><td>17</td></tr></table>
