# 

 
 # 题目描述 
<p align="left">给定一个无向连通图，其节点编号为&nbsp;1&nbsp;到&nbsp;N，其边的权值为非负整数。试求出一条从&nbsp;1&nbsp;号节点到&nbsp;N&nbsp;号节点的路径，使得该路径上经过的边的权值的&ldquo;XOR&nbsp;和&rdquo;最大。该路径可以重复经过某些节点或边，当一条边在路径中出现多次时，其权值在计算&ldquo;XOR&nbsp;和&rdquo;时也要被重复计算相应多的次数。</p>

<p align="left">直接求解上述问题比较困难，于是你决定使用非完美算法。具体来说，从&nbsp;1&nbsp;号节点开始，以相等的概率，随机选择与当前节点相关联的某条边，并沿这条边走到下一个节点，重复这个过程，直到走到&nbsp;N&nbsp;号节点为止，便得到一条从&nbsp;1&nbsp;号节点到&nbsp;N&nbsp;号节点的路径。显然得到每条这样的路径的概率是不同的并且每条这样的路径的&ldquo;XOR&nbsp;和&rdquo;也不一样。现在请你求出该算法得到的路径的&ldquo;XOR&nbsp;和&rdquo;的期望值。</p> 

 
 # 输入格式 
<p>输入文件的第一行是用空格隔开的两个正整数N和M，分别表示该图的节点数和边数。紧接着的M行，每行是用空格隔开的三个非负整数u，v和w(1&le;u,v&le;N，0&le;w&le;10^9)，表示该图的一条边(u,v)，其权值为w。输入的数据保证图连通，30%的数据满足N&le;30，100%的数据满足2&le;N&le;100，M&le;10000，但是图中可能有重边或自环。</p> 

 
 # 输出格式 
<p>仅包含一个实数，表示上述算法得到的路径的&ldquo;XOR&nbsp;和&rdquo;的期望值，要求保留三位小数。（建议使用精度较高的数据类型进行计算）</p> 

 
 # 提示 
<p align="left"><span style="line-height: 1.6em;">样例1解释：有1/2的概率直接从1号节点走到2号节点，该路径的&ldquo;XOR和&rdquo;为3；有1/4的概率从1号节点走一次1号节点的自环后走到2号节点，该路径的&ldquo;XOR和&rdquo;为1；有1/8的概率从1号节点走两次1号节点的自环后走到2号节点，该路径的&ldquo;XOR和&rdquo;为3；&bdquo;&bdquo;；依此类推，可知&ldquo;XOR和&rdquo;的期望值为：3/2+1/4+3/8+1/16+3/32+&bdquo;&bdquo;=7/3，约等于2.333。</span></p> 
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
<tr><td>2 2
1 1 2
1 2 3</td><td>2.333</td></tr><tr><td>3 3
1 2 4
1 3 5
2 3 6</td><td>4.000</td></tr></table>
