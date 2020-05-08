
# Content

众所周知，一个魔法总是有很多版本，而它们的威力、消耗等各有不同，为了能在需要时能使用合适的魔法版本以及开发新版本的魔法，大贤者为利姆露建立了魔法咒语库，在其中一种记录方式如下：
一个版本的魔法的相关信息被表示为一个 $n$ 位的数组，每次修改了某个版本的魔法后，魔法的某个数据改变（即数组的某个数改变），就产生一个新的魔法版本（初始版本为 $0$ 号，后新生成的版本依次编号）。
对该种记录方式，用以下的方式进行维护和查询：
- $\texttt{1 v x y}$：从 $v$ 号版本中，修改第 $x$ 个数为 $y$，产生一新版本。
- $\texttt{2 v x}$：查询 $v$ 号版本中第 $x$ 个数的值。

# Standard Input

第一行是两个非负整数 $n,m$；
接下来是一行 $n$ 个数，表示初始版本的魔法数据；
接下来是 $m$ 行，表示 $m$ 次操作，格式如前述。

# Standard Output

若干行，依次的询问结果。

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
<tr><td>9 8
1 3 1 5 7 8 6 2 10 
1 0 5 5
1 1 3 6
2 2 5
2 1 6
2 0 7
1 0 9 8
1 3 9 2
2 4 9
</td><td>5
8
6
2
</td></tr></table>


# Constraints

$1<n\le10^6,1<m\le10^5$

# Note



# Source


