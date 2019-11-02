# 

 
 # 题目描述 
树的直径，即这棵树中距离最远的两个结点的距离。每两个相邻的结点的距离为1，即父亲结点与儿子结点或儿子结点与父子结点之间的距离为1.有趣的是，从树的任意一个结点a出发，走到距离最远的结点b，再从结点b出发，能够走的最远距离，就是树的直径。树中相邻两个结点的距离为1。你的任务是：给定一棵树，求这棵树中距离最远的两个结点的距离。 

 
 # 输入格式 
输入共n行<BR>第一行是一个正整数n，表示这棵树的结点数<BR>接下来的n-1行，每行三个正整数a,b,w。表示结点a和结点b之间有一条边，长度为w<BR>数据保证一定是一棵树，不必判错。<BR> 

 
 # 输出格式 
输出共一行<BR>第一行仅一个数，表示这棵树的最远距离 

 
 # 提示 
10%的数据满足1&lt;=n&lt;=5<BR>40%的数据满足1&lt;=n&lt;=100<BR>100%的数据满足1&lt;=n&lt;=10000&nbsp;1&lt;=a,b&lt;=n&nbsp;1&lt;=w&lt;=10000Tgotmacp 
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
<tr><td>4
1 2 10
1 3 12
1 4 15</td><td>27</td></tr></table>
