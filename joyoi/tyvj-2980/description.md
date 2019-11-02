# 

 
 # 题目描述 
<p>
一棵有根树有N个结点，我们给这些结点由0到N-1编上号，其中结点0为根结点。这棵树上连接两个结点的边有一个权值。你的任务是找一个结点的子集S={s1,s2,…,sm} (0<m<N)，满足下面的要求：<br>a)	S不包含根结点，即0<si<N, 1<=i<=m；<br>b)	对于子集中任意一对结点si与sj，si与sj在树中只有唯一的一个公共祖先，即为根结点；<br>c)	与S对应有两个关联集合W={w1,w2,…,wm}与D={d1,d2,…,dm}，wi表示根结点到结点si所经过的路径权值之和，di则表示根结点到结点si所经过路径的边数。<br>d)	令K=∑wi / ∑di (1<=i<=m)，你找的子集必须让K值尽可能的大。<br></p> 

 
 # 输入格式 
<p>
输入第一行为一个整数n（2<=n<=300），为树的顶点数。接下来n-1行每行3个整数u、v、w（0<=u, v<n，0<w<1,000,000），表示连接结点u与结点v的边权值是w。</p> 

 
 # 输出格式 
<p>
输出最大的K值，答案保留2位小数。</p> 
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
<tr><td>3
0 1 1
0 2 2
</td><td>2.00</td></tr></table>
