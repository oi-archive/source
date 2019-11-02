# 

 
 # 题目描述 
<p>
　　经过谢老师n次的教导，dfc终于觉悟了——过于腐败是不对的。但是dfc自身却无法改变自己，于是他找到了你，请求你的帮助。<br> dfc的内心可以看成是5*5个分区组成，每个分区都可以决定的的去向，0表示继续爱好腐败，1表示改正这个不良的习惯。只有当25个分区都为1时，dfc才会改正腐败这个不良习惯。你有一根神奇的魔法棒，可以使点中的分区以及这个分区上下左右改变（1变0,0变1）。这根神奇的魔法棒只能使用6次了，请问你最少使用多少次才可以救醒这dfc。（使用超过6次则输出-1，表示dfc已经无药可救了）。（因为dfc实在太顽固不化，所以你要救醒他n次，但每次都有会获得由谢老师送的一根新的魔法棒,不过之前那根会消失）。<br><br><center><img src="/source/joyoi/tyvj-3313/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMxMy9wcm9ibGVtc19pbWFnZXMvMjA0OS8xLmJtcA==.bmp"></img></center>　</p> 

 
 # 输入格式 
<p>
　　第一行有一个正整数n，代表数据中共有n组数据。<br>　　以下若干行数据分为n组，每组数据有5行，每行5个字符。每组数据描述了25个分区的初始状态。各组数据间用一个空行分隔。<br></p> 

 
 # 输出格式 
<p>
　　输出数据一共有n行，每行有一个小于等于6的整数，它表示对于输入数据中对应的每组数据最少需要几步才能将救醒dfc。<br>　　对于一个数据，如果无法在规定的条件救醒dfc，请输出“-1”。<br></p> 

 
 # 提示 
<p>
　　30%，n <= 5；<br>　　100%，n <= 500。<br><br><br></p> 
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
<tr><td>输入样例：
3
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
</td><td>输出样例：
3
2
-1</td></tr></table>
