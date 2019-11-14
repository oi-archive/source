
# Content

神奇的电子科技大学长着一棵神奇的树。

这棵树一共有$n+1$个节点，从$0$号到$n$号，每条边上有一个字符$c\_i$。

一日天行廖在校园内游历，见到这棵树，忽然想到了一个问题。

定义$s\_i$为从根节点到$i$的路径所构成的字符串。

对于每个节点$i$，天行廖想知道一个数$f(i)!=i$，使得$s\_{f(i)}$是$s\_i$的最长后缀。

# Standard Input

输入一个整数$1<=n<=200000$，接下来两行。

第一行$n$个整数，$p\_1,p\_2,\cdots,p\_n$，$0<=p\_i<i$，$p\_i$表示$i$的父亲

第二行$n$个整数，$c\_1,c\_2,\cdots,c\_n$，$1<=c\_i<=n$，$c\_i$表示$i$向其父亲连的边上的字符。

输入保证对于所有$i!=j$，$(p\_i,c\_i)!=(p\_j,c\_j)$

# Standard Output

输出$n$个数，$f(1),f(2),\cdots,f(n)$

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
<tr><td>2
0 0
1 2</td><td>0 0</td></tr><tr><td>2
0 1
1 1</td><td>0 1</td></tr></table>


# Constraints



# Note



# Source


