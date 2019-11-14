# 

 
 # 题目背景 
快要期中考试了！老师需要hzy帮他排考试的座位。。。<br> 

 
 # 题目描述 
考场里的座位恰好有n行m列，并且恰好有n*m位考生在这个考场里面考试，也就是说，所有的座位上都有考生。hzy根据学校记载，有k位考生可能作弊，因此hzy不能让他们之中的任何两个人做在相邻的座位上！所谓相邻的座位，即在同一行相邻列或者在同一列的相邻行的座位。hzy准备这样安排座位，首先随机选择一种方案，如果这种方案是合法的，就用这种方案，否则重新选择。你的任务是计算，他得到一个合法方案时，需要的期望选择次数。&nbsp;<br> 

 
 # 输入格式 
输入文件为一行，仅包含三个整数n，m和k。<br> 

 
 # 输出格式 
如果不存在合法的方案，则输出中应该包含Impossible!，否则输出一个分数p/q，表示期望选择次数(即平均次数)，这里p和q应该是互质的。<br> 

 
 # 提示 
1≤n≤80，1≤m≤80，1≤n*m≤80<br>0≤k≤20，并且k≤n*m&nbsp;<br> 
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
<tr><td>input1
1 4 3
input2
2 3 2 
</td><td>input1
Impossible!
input2
15/8
</td></tr></table>
