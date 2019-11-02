# 

 
 # 题目背景 
USACO&nbsp;2011&nbsp;January&nbsp;金组<BR> 

 
 # 题目描述 
Farmer&nbsp;John正在一个新的销售区域对他的牛奶销售方案进行调查。他想把牛奶送到T个城镇&nbsp;(1&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;25,000)，编号为1T。这些城镇之间通过R条道路&nbsp;(1&nbsp;&lt;=&nbsp;R&nbsp;&lt;=&nbsp;50,000，编号为1到R)&nbsp;和P条航线&nbsp;(1&nbsp;&lt;=&nbsp;P&nbsp;&lt;=&nbsp;50,000，编号为1到P)&nbsp;连接。每条道路i或者航线i连接城镇A_i&nbsp;(1&nbsp;&lt;=&nbsp;A_i&nbsp;&lt;=&nbsp;T)到B_i&nbsp;(1&nbsp;&lt;=&nbsp;B_i&nbsp;&lt;=&nbsp;T)，花费为C_i。对于道路，0&nbsp;&lt;=&nbsp;C_i&nbsp;&lt;=&nbsp;10,000;然而航线的花费很神奇，花费C_i可能是负数(-10,000&nbsp;&lt;=&nbsp;C_i&nbsp;&lt;=&nbsp;10,000)。道路是双向的，可以从A_i到B_i，也可以从B_i到A_i，花费都是C_i。然而航线与之不同，只可以从A_i到B_i。事实上，由于最近恐怖主义太嚣张，为了社会和谐，出台&nbsp;<BR>了一些政策保证：如果有一条航线可以从A_i到B_i，那么保证不可能通过一些道路和航线从B_i回到A_i。由于FJ的奶牛世界公认十分给力，他需要运送奶牛到每一个城镇。他想找到从发送中心城镇S(1&nbsp;&lt;=&nbsp;S&nbsp;&lt;=&nbsp;T)&nbsp;把奶牛送到每个城镇的最便宜的方案，或者知道这是不可能的。&nbsp;<BR><BR><BR> 

 
 # 输入格式 
*&nbsp;第1行：四个空格隔开的整数:&nbsp;T,&nbsp;R,&nbsp;P,&nbsp;and&nbsp;S&nbsp;<BR><BR>*&nbsp;第2到R+1行：三个空格隔开的整数（表示一条道路）：A_i,&nbsp;B_i&nbsp;和&nbsp;C_i&nbsp;<BR><BR>*&nbsp;第R+2到R+P+1行：三个空格隔开的整数（表示一条航线）：A_i,&nbsp;B_i&nbsp;和&nbsp;C_i&nbsp;<BR> 

 
 # 输出格式 
*&nbsp;第1到T行：从S到达城镇i的最小花费，如果不存在输出"NO&nbsp;PATH"。&nbsp;<BR> 

 
 # 提示 
J的奶牛从4号城镇开始，可以通过道路到达3号城镇。然后他们会通过航线达到5和6号城镇。&nbsp;<BR>但是不可能到达1和2号城镇。<BR><BR>温馨提示：SPFA会TLE滴...USACO&nbsp;2011&nbsp;January&nbsp;金组<BR> 
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
<tr><td>6 3 3 4
1 2 5
3 4 5
5 6 10
3 5 -100
4 6 -100
1 3 -10
</td><td>NO PATH
NO PATH
5
0
-95
-100

</td></tr></table>
