# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;你玩过“拉灯”游戏吗？25盏灯排成一个5x5的方形。每一个灯都有一个开关，游戏者可以改变它的状态。每一步，游戏者可以改变某一个灯的状态。游戏者改变一个灯的状态会产生连锁反应：和这个灯上下左右相邻的灯也要相应地改变其状态。<BR>&nbsp;&nbsp;&nbsp;&nbsp;我们用数字“1”表示一盏开着的灯，用数字“0”表示关着的灯。下面这种状态<BR><BR>10111<BR>01101<BR>10111<BR>10000<BR>11011<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;在改变了最左上角的灯的状态后将变成：<BR><BR>01111<BR>11101<BR>10111<BR>10000<BR>11011<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;再改变它正中间的灯后状态将变成：<BR><BR>01111<BR>11001<BR>11001<BR>10100<BR>11011<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;给定一些游戏的初始状态，编写程序判断游戏者是否可能在6步以内使所有的灯都变亮。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行有一个正整数n，代表数据中共有n个待解决的游戏初始状态。<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下若干行数据分为n组，每组数据有5行，每行5个字符。每组数据描述了一个游戏的初始状态。各组数据间用一个空行分隔。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于30%的数据，n&lt;=5；<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，n&lt;=500。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出数据一共有n行，每行有一个小于等于6的整数，它表示对于输入数据中对应的游戏状态最少需要几步才能使所有灯变亮。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于某一个游戏初始状态，若6步以内无法使所有灯变亮，请输出“-1”。 

 
 # 提示 
Matrix67原创 
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
<tr><td>3
00111
01011
10001
11010
11100

11101
11101
11110
11111
11111

01111
11111
11111
11111
11111
</td><td>3
2
-1</td></tr></table>
