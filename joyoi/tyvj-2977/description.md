# 

 
 # 题目描述 
<p>
　　设有n个大小不等的中空圆盘，按从小到大的顺序从1到n编号。将这n个圆盘任意的迭套在三根立柱上，立柱的编号分别为A、B、C，这个状态称为初始状态。<br>　　现在要求找到一种步数最少的移动方案，使得从初始状态转变为目标状态。<br>　　移动时有如下要求：<br>　　　&#8226;一次只能移一个盘；<br>　　　&#8226;不允许把大盘移到小盘上面。<br></p> 

 
 # 输入格式 
<p>
　　文件第一行是状态中圆盘总数；<br>　　第二到第四行分别是初始状态中A、B、C柱上圆盘的个数和从上到下每个圆盘的编号；<br>　　第五到第七行分别是目标状态中A、B、C柱上圆盘的个数和从上到下每个圆盘的编号。<br></p> 

 
 # 输出格式 
<p>
　　一行，输出最少的步数。（答案保证在integer范围内）<br></p> 

 
 # 提示 
<p>
样例的移动序列：<br>move 1 from A to B<br>move 2 from A to C<br>move 1 from B to C<br>move 3 from A to B<br>move 1 from C to B<br>move 2 from C to A<br>move 1 from B to C<br></p> 
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
<tr><td>5					
3 3 2 1				
2 5 4				
0					
1 2					
3 5 4 3				
1 1					
						</td><td>7</td></tr></table>
