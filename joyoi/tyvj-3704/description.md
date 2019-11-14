# 

 
 # 题目描述 
<p><a href="http://cexou.img48.wal8.com/img48/543212_20160415183019/146297118226.jpg"><img alt="" src="/source/joyoi/tyvj-3704/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzcwNC9odHRwOi8vY2V4b3UuaW1nNDgud2FsOC5jb20vaW1nNDgvNTQzMjEyXzIwMTYwNDE1MTgzMDE5L3MvMTQ2Mjk3MTE4MjI2X21lZGl1bS5qcGc=.jpg" style="width: 640px; height: 1562px;" /></a></p> 

 
 # 输入格式 
<p>第一行包含两个整数&nbsp;N,M，分别表示树的节点数和操作个数。接下来&nbsp;N-1&nbsp;行，每行两个数&nbsp;u,v，表示有一条连接节点&nbsp;u,v&nbsp;的边，这条边上恰好包含一个电阻。&nbsp;</p>

<p>接下来&nbsp;M&nbsp;行，每行一个命令，格式见题目描述。&nbsp;</p> 

 
 # 输出格式 
<p>对于每个&nbsp;Q&nbsp;命令，输出一个数表示此刻该点的电压值。你可以输出任意多位的小数，只要你的答案和标准答案相差不超过&nbsp;10-3&nbsp;就算合法。&nbsp;</p> 

 
 # 提示 
<h3>样例说明</h3>

<p>对于第一个询问，由于原图中没有电源，所以没有电流，所有点的电压都相等（否则如果有&nbsp;Ui&gt;Uj，则就有&nbsp;i&nbsp;流向&nbsp;j&nbsp;的电流，与没有电源矛盾）,都等于地电压&nbsp;0V。&nbsp;</p>

<p>之后在&lt;2,4&gt;中加一个&nbsp;5V&nbsp;的电源，得到的新图见题目描述。&nbsp;</p>

<p>整理后可以发现，新图的形式是串联&nbsp;(电源,R2+10000,并联(R1+10000,&nbsp;R3+10000))，由此可以得到新图的总电阻为:&nbsp;<br />
R2+10000+1/(1/(R3+10000)+1/(R1+10000))=30000&nbsp;&Omega;.&nbsp;</p>

<p>所以流过节点&nbsp;4&nbsp;的电流就是&nbsp;5/30000A，所以&nbsp;U4=5/3V。U2=U4+R2*I-5=-5/3V，由于&nbsp;U1&nbsp;和&nbsp;U3形式对称，由分压关系可知&nbsp;U1=U3=U2*10000/(10000+10000)=-5/6V。&nbsp;</p>

<h3>数据规模</h3>

<p>30%的数据保证&nbsp;N,M&nbsp;&le;&nbsp;30</p>

<p>60%的数据保证&nbsp;N,M&nbsp;&le;&nbsp;3000&nbsp;</p>

<p>100%的数据保证&nbsp;3&nbsp;&le;&nbsp;N,M&nbsp;&le;&nbsp;50000，1&nbsp;&le;&nbsp;u,v&nbsp;&le;&nbsp;n，1&nbsp;&le;&nbsp;w&nbsp;&le;&nbsp;10，树中最长链的长度不超过&nbsp;50。&nbsp;</p> 
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
<tr><td>4 3
1 2
2 3
2 4
Q 2
C 2 4 5
Q 2
</td><td>0.0000000000
-1.6666666666
</td></tr></table>
