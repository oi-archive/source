# 

 
 # 题目背景 
NOIP2005&nbsp;提高组&nbsp;第二道 

 
 # 题目描述 
　　在河上有一座独木桥，一只青蛙想沿着独木桥从河的一侧跳到另一侧。在桥上有一些石子，青蛙很讨厌踩在这些石子上。由于桥的长度和青蛙一次跳过的距离都是正整数，我们可以把独木桥上青蛙可能到达的点看成数轴上的一串整点：0，1，……，L（其中L是桥的长度）。坐标为0的点表示桥的起点，坐标为L的点表示桥的终点。青蛙从桥的起点开始，不停的向终点方向跳跃。一次跳跃的距离是S到T之间的任意正整数（包括S,T）。当青蛙跳到或跳过坐标为L的点时，就算青蛙已经跳出了独木桥。&nbsp;<BR><BR>　　题目给出独木桥的长度L，青蛙跳跃的距离范围S,T，桥上石子的位置。你的任务是确定青蛙要想过河，最少需要踩到的石子数。&nbsp;<BR><BR>　　对于30%的数据，L&nbsp;&lt;=&nbsp;10000；&nbsp;<BR>　　对于全部的数据，L&nbsp;&lt;=&nbsp;10^9。 

 
 # 输入格式 
　　输入的第一行有一个正整数L（1&nbsp;&lt;=&nbsp;L&nbsp;&lt;=&nbsp;10^9），表示独木桥的长度。第二行有三个正整数S，T，M，分别表示青蛙一次跳跃的最小距离，最大距离，及桥上石子的个数，其中1&nbsp;&lt;=&nbsp;S&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;10，1&nbsp;&lt;=&nbsp;M&nbsp;&lt;=&nbsp;100。第三行有M个不同的正整数分别表示这M个石子在数轴上的位置（数据保证桥的起点和终点处没有石子）。所有相邻的整数之间用一个空格隔开。&nbsp;<BR> 

 
 # 输出格式 
　　输出只包括一个整数，表示青蛙过河最少需要踩到的石子数。&nbsp;<BR> 
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
<tr><td>10
2 3 5
2 3 5 6 7
</td><td>2</td></tr></table>
