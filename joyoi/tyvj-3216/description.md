# 

 
 # 题目描述 
<p>
最长k可重区间集问题(interv.cpp/c/pas)<br><br>【问题描述】<br><br>　　给定实直线L 上n 个开区间组成的集合I，和一个正整数k，试设计一个算法，从开区间集合I 中选取出开区间集合<img src="/source/joyoi/tyvj-3216/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxNi9wcm9ibGVtc19pbWFnZXMvMTYyNC9wMi5naWY=.gif"></img>，使得在实直线L 的任何一点x，S 中包含点x 的开区间个数不超过k，且<img src="/source/joyoi/tyvj-3216/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxNi9wcm9ibGVtc19pbWFnZXMvMTYyNC9wMS5naWY=.gif"></img>达到最大。这样的集合S称为开区间集合I的最长k可重区间集。<img src="/source/joyoi/tyvj-3216/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxNi9wcm9ibGVtc19pbWFnZXMvMTYyNC9wMS5naWY=.gif"></img>称为最长k可重区间集的长度。<br><br>【编程任务】<br><br>　　对于给定的开区间集合I和正整数k，计算开区间集合I的最长k可重区间集的长度。</p> 

 
 # 输入格式 
<p>
由文件interv.in提供输入数据。<br>　　文件的第1 行有2 个正整数n和k，分别表示开区间的个数和开区间的可重迭数。接下来的n行，每行有2个整数，表示开区间的左右端点坐标。</p> 

 
 # 输出格式 
<p>
程序运行结束时，将计算出的最长k可重区间集的长度输出到文件interv.out中。<br></p> 
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
1 7
6 8
7 10
9 13</td><td>15</td></tr></table>
