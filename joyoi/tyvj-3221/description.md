# 

 
 # 题目描述 
<p>
【问题描述】<br>　　假如坦佩雷区域的第四代手机基站运转如下。该区域被分为若干方块。所有方块构成一个S * S 的矩阵，其行号和列号都为0 到 S-1。每个方块包含一个基站。方块中活跃的手机数量经常改变，因为有些手机从一个方块转移到了另一个方块，又或者手机开关机。有时候，每个基站向总站报告其所在方块中活跃手机数目的变化情况。<br>　　写一个程序，接受这些报告，并回答有关指定矩形区域内一共有多少活跃手机的询问。 <br></p> 

 
 # 输入格式 
<p>
　　输入编码如下表。每个输入单独为一行，包含一个指令（Instruction）和若干参数（Parameters）。<br><br><br><center><img src="/source/joyoi/tyvj-3221/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIyMS9wcm9ibGVtc19pbWFnZXMvMTcwMy9wMS5naWY=.gif"></img></center><br><br>　　所有取值都不会超出合法范围，所以不必进行检验。特别地，你可以认为任意方块中的手机总数不会小于0。下标索引从0开始。例如：4*4的矩阵，满足0 <= X <= 3 以及 0 <= Y <= 3。<br><br>　　矩阵尺寸： 1 * 1 <= S * S <= 1024 * 1024 <br>　　单一方块任何时刻的取值V： 0 <= V <= 32767 <br>　　每次更新的数值：-32768 <= A <= 32767 <br>　　指令的总数：3 <= U <= 60002 <br>　　矩阵中的手机总数的最大值：M= 2^30 <br></p> 

 
 # 输出格式 
<p>
　　你的程序要回答每一个询问（指令编号为2），对于其他指令不能输出任何内容。回答询问，必须在单独一行输出一个整数，表示矩形区域内的手机总数。</p> 
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
<tr><td>0 4
1 1 2 3
2 0 0 2 2 
1 1 1 2
1 1 2 -1
2 1 1 2 3 
3
</td><td>3
4</td></tr></table>
