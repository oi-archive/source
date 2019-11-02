# 

 
 # 题目描述 
<p>
问题描述：<br>　　贪玩的chnlkw得到了许多礼物，其中他最喜欢的是一个游戏棋，游戏棋的规则是这样的：<br>　　这是一张n×m的棋盘，上面放有一些棋子。<br><br><center><img src="/source/joyoi/tyvj-3324/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMyNC9wcm9ibGVtc19pbWFnZXMvMjA2NS8xLmJtcA==.bmp"></img></center>　<br>　　每走一步的规则如下：取一颗棋子越过与它相邻（上下左右）的一颗棋子落下，拿走越过的那颗棋子。直到棋盘上剩下一颗棋子时获胜。<br>（棋子不能走到棋盘外 XXX：废话。）<br>如图：<br><br><center><img src="/source/joyoi/tyvj-3324/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMyNC9wcm9ibGVtc19pbWFnZXMvMjA2NS8yLmJtcA==.bmp"></img></center>　 <br>　　Chnlkw对这个游戏十分感兴趣，但他不愿意自已来下。他想请教你来编一个程序告诉他能否获得这个游戏的胜利。<br></p> 

 
 # 输入格式 
<p>
　　第一行是2个正整数n，m（n,m <= 10）<br>　　接下来n行，每行有长度为m的01串，0表示棋盘这个位置上没有棋子，1表示有棋子。<br></p> 

 
 # 输出格式 
<p>
　　输出只有一行，如果这盘棋能获胜则输出最少需走的步数，否则先后输出“impossible”（引号舍去）以及最多能行走的步数，各占一行。<br></p> 
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
<tr><td>6 5
00000
00100
01110
00100
00100
00000
</td><td>5</td></tr></table>
