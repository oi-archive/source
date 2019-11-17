# 

 
 # 题目背景 
<p>NOIP2010普及组模拟赛！</p> 

 
 # 题目描述 
<p>19世纪的时候，Moriz&nbsp;Stern与Achille&nbsp;Brocot发明了&ldquo;一棵树&rdquo;。据说，经由一些简单的规则而产生的这一棵树上，可以包含0以上所有的有理数。这棵树看起来大致这样.<br />
<img align="middle" border="0" src="/source/joyoi/tyvj-1446/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTQ0Ni9odHRwOi8vd3d3LngtZmVuZy5jb20vb2kvT0ovUHJvYmxlbUltZy8xMzIzLnBuZw==.png" /><br />
你观察出规则了么？<br />
首先，在第一列放两个&ldquo;分数&rdquo;，第一个是0/1代表0；第二个是1/0代表无穷大。接着它们一列一列的产生这棵树，当它们产生第k+1列的时候，就先把前k列所有的分数按照大小排成1列（假设有n个），在这些数之间会有n-1个间隔，那么第k+1列就准备产生n-1个数，其值得分子正好是左右两个数的分子之和，分母是左右两个数的分母之和。<br />
例如：2//3，分子2正好是左边的1/2的分子1和右边的1/1的分子相加的结果；而2/3的3正好是1/2的2和1/1的分母的1相加而得。<br />
从这棵树中，我们可以看出，每个正的最简分数在数中恰好出现1次，我们用字母L和R分别表示从树根1/1开始的一步，&ldquo;向左走&rdquo;和&ldquo;向右走&rdquo;，则没一个数都可以由L和R组成的序列表示。<br />
例如，LRRL表示从1/1开始向左走一步到1/2，然后向右走一步到2/3，在往右走一步到3//4，最后向左走一步到5/7。我们把LRRL看作5//7的一种表示方法，几乎每个正分数都有唯一的方法表示成L和R组成的序列。<br />
给定i个分数，给出它的LR表示法。<br />
&nbsp;</p> 

 
 # 输入格式 
<p>第一行自然数i,<br />
下面i行每行两个自然数n和m(0&lt;=n,m&lt;=10000)</p> 

 
 # 输出格式 
<p>每行一个字符串，即LR表示法<br />
共i行</p> 

 
 # 提示 
<p>i&lt;=10000,n,m&lt;=10000,且n与m互质</p> 
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
3 5
</td><td>LRL
</td></tr></table>
