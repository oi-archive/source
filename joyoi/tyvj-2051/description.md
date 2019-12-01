# 

 
 # 题目描述 
NOIP提高组初赛考了“树的独立集”问题，于是我们反其道而行之，研究一下树的子树问题。<br>我们知道，树是含有n个节点，n-1条边的特殊连通图。<br>如果树A包含的点的集合是树T包含的点的集合的子集，那么树A是树T的一棵“子树”。<br>定义树T的两棵子树A、B不同，当且仅当“存在一个节点u属于子树A不属于子树B，或存在一个节点v属于子树B不属于子树A”。<br>给出一棵无向无根树，求这棵树的不同的子树有多少个呢？<br> 

 
 # 输入格式 
测试数据包含多组。<br>第一行一个整数T，表示测试数据的数目。<br>对于每组测试数据：<br>	第一行一个整数N，表示给出树的节点数。<br>	接下来N-1行每行两个整数a,b,表示节点a和节点b之间有一条边。<br> 

 
 # 输出格式 
输出T行，对于每组测试数据，输出一行一个答案ans，表示给出无向无根树的子树的个数。由于这个数可能很大，你只需要输出ans对1000000007取模的结果。<br> 

 
 # 提示 
样例解释：<br>显然有如下6棵子树：<br>{1}&nbsp;{2}&nbsp;{3}&nbsp;{1,2}&nbsp;{1,3}&nbsp;{1,2,3}<br>{2,3}不满足条件因为集合中的点不连通。<br>数据范围：<br>T&nbsp;&lt;=&nbsp;50<br>N&nbsp;&lt;=&nbsp;100000<br>zanoes提供出题思路,This_poet描述题目.<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com<br> 
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
<tr><td>1
3
1 2
1 3
</td><td>6
</td></tr></table>
