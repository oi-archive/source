# 

 
 # 题目背景 
经典题目 

 
 # 题目描述 
1920年的芝加哥，出现了一群强盗。如果两个强盗遇上了，那么他们要么是朋友，要么是敌人。&nbsp;<BR>而且有一点是肯定的，就是A的朋友的朋友是A的朋友；A的敌人的敌人也是A的朋友。&nbsp;<BR>两个强盗是同一伙的当且仅当他们是朋友。现在给你一些关于强盗们的信息，问你至多有多少个强盗团伙。<BR> 

 
 # 输入格式 
输入的第一行为N(2&lt;=N&lt;=1000)，表示强盗的个数（从1编号到N）。&nbsp;<BR>第二行M(1&lt;=M&lt;=5000)，表示信息条数。&nbsp;<BR>以下M行，每行可能是F&nbsp;p&nbsp;q或是E&nbsp;p&nbsp;q，分别表示p和q是朋友，或是敌人。&nbsp;<BR>假设输入不会产生矛盾<BR> 

 
 # 输出格式 
输出只有一行，表示最大可能的团伙数。 
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
<tr><td>6
4
E 1 4
F 3 5
F 4 6
E 1 2
</td><td>3</td></tr></table>
