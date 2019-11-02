# 题目背景
XRJ大佬最喜欢怼大鸨了，现在他有n件事情可以来怼大鸨，每次怼大鸨只能说连续的k件事情，第i件事情可以激起大鸨a[i]点怒气值，当大鸨怒气值大于等于s时，XRJ就算怼成功了。但是XRJ不喜欢费太多口舌，所以他希望少说几件事，但这些事情又必须是连续的。请输出最小需要说连续的几件事才能成功怼大鸨。

# 题目描述
输入n个正整数，其中有连续k个数的和不小于s，求最小的k。

# 输入格式

每组输入数据共有两行。

第一行两个整数n,s。

第二行输入n个正整数，表示第i件事可以激起大鸨a[i]点怒气值。

# 输出格式
一行一个整数，表示最少说的事件数k。# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>5 7
4 1 2 5 1</td><td>2</td></tr></table>
