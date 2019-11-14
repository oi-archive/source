# 

 
 # 题目描述 
faith看着看着玻璃窗竟然睡着了。于是他来到了梦境。<BR>梦境中自己正在打红警，由于自己的主基地和车场都被炸了。自己没办法造出坦克，faith不得不造出来尽量多的碉堡来保卫自己。faith的基地在一个N*M的矩形区域上，这个地方已经造好了faith的一些建筑（用'X'表示,空地用'.'表示），他不能在这些地方放置碉堡。对于这个梦境的红警，碉堡是非常奇葩的--两个都是自己的碉堡，如果在射程范围内，会自相残杀。碉堡的攻击范围也是非常奇葩的，如果一个碉堡的坐标是&nbsp;(x,y)&nbsp;那么&nbsp;(x-2,y)(x-1,y)(x,y)(x+1,y)(x+2,y)(x,y-2)(x,y-1)(x,y+1)(x,y+2)&nbsp;都是他的攻击范围（只能上下左右两个格子，不能斜着攻击）。由于faith有许许多多的钱，现在请你帮他算算，他最多能造多少个碉堡（不能让碉堡自相残杀） 

 
 # 输入格式 
输入第一行两个数&nbsp;N&nbsp;M&nbsp;表示N行M列，之后是一个N*M的矩阵。 

 
 # 输出格式 
输出一行，表示最多放置碉堡的数目。 

 
 # 提示 
数据范围：<BR>n&lt;=100<BR>m&lt;=10 
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
<tr><td>5 4
.X..
..XX
....
.X..
.XX.
</td><td>6
</td></tr></table>
