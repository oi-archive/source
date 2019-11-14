# 

 
 # 题目背景 
noip2011&nbsp;提高组&nbsp;初赛<BR> 

 
 # 题目描述 
（笛卡尔树）对于一个给定的两两不等的正整数序列，笛卡尔树是这样的一棵二叉树：首先，它是一个最小堆，即除了根结点外，每个结点的权值都大于父节点的权值；其次，它的中序遍历恰好就是给定的序列。例如，对于序列&nbsp;7、2、12、1、10、5、15、3，下图就是一棵对应的笛卡尔树。现输入序列的规模&nbsp;n（1≤n&lt;100）和序列的&nbsp;n&nbsp;个元素，试求其对应的笛卡尔树的深度&nbsp;d（根节点深度为&nbsp;1），以及有多少个叶节点的深度为&nbsp;d。 

 
 # 输入格式 
输入格式：<BR>第一行&nbsp;1个数n（含义如上题）<BR>第二行&nbsp;n个数，表示这个正整数序列<BR> 

 
 # 输出格式 
输出格式：<BR>一行&nbsp;深度d&nbsp;以及有多少个叶节点的深度为&nbsp;d。 

 
 # 提示 
数据范围<BR>1&lt;=n&lt;100<BR>1&lt;=a[i]&lt;=100000<BR>CCF.. 
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
42 18468 6335 26501 19170 
</td><td>4 1
</td></tr></table>
