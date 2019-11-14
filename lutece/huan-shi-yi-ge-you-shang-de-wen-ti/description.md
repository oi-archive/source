
# Content

对于任意一个正整数$n$，都可以进行质因数分解。即写成这样的形式$n=p\_1^{k\_1}\times p\_2^{k\_2}\times \cdots \times p\_r^{k\_r}$

请相信上面那段是废话。。

我们定义一种因子二叉树，因子二叉树需要满足这样的几个条件：
1. 这是一棵二叉树，并且每个非叶子节点都必须存在一个左儿子和右女儿（必须要一男一女哦）
2. 每个结点都有一个值$val$，并且一个结点是叶子结点的充分必要条件是该结点的$val$是一个素数。
3. 对于每一个非叶子结点，左儿子的$val$和右女儿的$val$的乘积是该结点的$val$。

如果根结点的$val$值为$N$，那么我们称这个树是一颗根结点为$N$的因子二叉树。

现在给你一个$N$，请你求出有多少棵不同的根节点为$N$的因子二叉树。

# Standard Input

不超过$10000$组样例。每组样例输入一行，只包含一个$N$。 ($2\leq N\leq 10^9$)

# Standard Output

对于每一组样例，输出根节点为$N$的因子二叉树的个数。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>12
108
642485760</td><td>6
140
9637611984000</td></tr></table>


# Constraints



# Note



# Source


