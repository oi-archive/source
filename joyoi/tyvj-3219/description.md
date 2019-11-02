# 

 
 # 题目描述 
<p>
骑士共存问题（kni.pas/c/cpp）<br><br>【问题描述】<br><br>　　在一个n*n个方格的国际象棋棋盘上，马（骑士）可以攻击的棋盘方格如图所示。棋盘上某些方格设置了障碍，骑士不得进入。<br><br><center><img src="/source/joyoi/tyvj-3219/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxOS9wcm9ibGVtc19pbWFnZXMvMTYyNy9wMS5naWY=.gif"></img></center><br><br>【编程任务】<br><br>　　对于给定的n*n个方格的国际象棋棋盘和障碍标志，计算棋盘上最多可以放置多少个骑士，使得它们彼此互不攻击。</p> 

 
 # 输入格式 
<p>
由文件kni.in给出输入数据。<br>　　第一行有2 个正整数n 和m (1<=n <=200, 0<=m < n2)，分别表示棋盘的大小和障碍数。接下来的m 行给出障碍的位置。每行2 个正整数，表示障碍的方格坐标。</p> 

 
 # 输出格式 
<p>
将计算出的共存骑士数输出到文件kni.out。</p> 
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
<tr><td>3 2
1 1
3 3</td><td>5</td></tr></table>
