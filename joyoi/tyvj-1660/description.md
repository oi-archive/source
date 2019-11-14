# 

 
 # 题目描述 
新学期开学了，高一的小朋友们蹦蹦跳跳的入学了，oi小组也开始招收新同学了！<BR>由于今年的宣传很到位，有n个来报名的小朋友。已知一个负责报名的人在同一时间内只能接待一个小朋友，并且因为每个人的个人“素质”不同，报名的用时是不同的（比如：loli就比凤姐用时间长）。有些意志特别不坚定的小朋友会因为等待时间太长而放弃报名，所以中中想要使平均等待时间最短。<BR>中中现在想知道1.如果只有他一个人负责报名的最短平均等待时间<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.如果他让手下k名OIer负责报名的最短平均等待时间<BR>已知n个人的报名用时，请你回答中中的问题。<BR>注意:1.一旦有OIer帮忙则中中就只负责大局而不负责报名了<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.一个人的报名时间也算在这个人的等待时间里 

 
 # 输入格式 
第一行两个整数n,k，n表示报名的小朋友数，k表示中中打算拉上的Oier<BR>接下来的一行有n个整数，表示n个小朋友的报名用时<BR> 

 
 # 输出格式 
输出文件有且仅有两行。<BR>第一行输出只有中中负责报名的最短平均用时<BR>第二行输出有k个OIer帮忙的最短平均用时<BR>输出保留小数点后2位,注意四舍五入<BR> 

 
 # 提示 
&nbsp;40%的数据&nbsp;n≤400&nbsp;&nbsp;&nbsp;k≤100<BR>&nbsp;60%的数据&nbsp;n≤5000&nbsp;&nbsp;k≤700<BR>100%的数据&nbsp;n≤10000&nbsp;k≤1000<BR><BR><BR><BR> 
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
<tr><td>10 2
56 12 1 99 1000 234 33 55 99 812
</td><td>532.00
336.00
</td></tr></table>
