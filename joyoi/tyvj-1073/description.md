# 

 
 # 题目背景 
<p>NOIP2003&nbsp;提高组&nbsp;第三道</p> 

 
 # 题目描述 
<p>设一个n个节点的二叉树tree的中序遍历为（l,2,3,&hellip;,n），其中数字1,2,3,&hellip;,n为节点编号。每个节点都有一个分数（均为正整数），记第j个节点的分数为di，tree及它的每个子树都有一个加分，任一棵子树subtree（也包含tree本身）的加分计算方法如下：<br />
&nbsp;&nbsp;&nbsp;&nbsp;subtree的左子树的加分&times;&nbsp;subtree的右子树的加分＋subtree的根的分数<br />
&nbsp;&nbsp;&nbsp;&nbsp;若某个子树为主，规定其加分为1，叶子的加分就是叶节点本身的分数。不考虑它的空<br />
子树。<br />
&nbsp;&nbsp;&nbsp;&nbsp;试求一棵符合中序遍历为（1,2,3,&hellip;,n）且加分最高的二叉树tree。要求输出；<br />
&nbsp;&nbsp;&nbsp;&nbsp;（1）tree的最高加分<br />
&nbsp;&nbsp;&nbsp;&nbsp;（2）tree的前序遍历</p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;第1行：一个整数n（n＜30），为节点个数。<br />
&nbsp;&nbsp;&nbsp;&nbsp;第2行：n个用空格隔开的整数，为每个节点的分数（分数＜100）。</p> 

 
 # 输出格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;第1行：一个整数，为最高加分（结果不会超过4,000,000,000）。<br />
&nbsp;&nbsp;&nbsp;&nbsp;第2行：n个用空格隔开的整数，为该树的前序遍历。</p> 
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
5 7 1 2 10
</td><td>145
3 1 2 4 5
</td></tr></table>
