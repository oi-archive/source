
# Content

由于上次的游戏中`学霸周`输了，因此`学霸周`想出个问题为难`天才钱`，问题是这样的，有一个$n\times m$的矩阵，每一个格子中有一个整数，`周大爷`给出了数组$A[1\cdots n]$($A[i]$表示第$i$行的元素之和)以及数组$B[1\cdots m]$ ($B[i]$表示第$i$列的元素之和)，现在`周大爷`问`钱大爷`能否给每个格子$(i,j)$填一个整数$p[i][j]$（$1\le p[i][j]\le 20$）使得满足`周大爷`一开始给出的两个数组。`钱大爷`觉得暴力都可以啊，所以他不想解决这么easy的问题。现在，他决定把问题交给你。

# Standard Input

第一行两个整数$n$，$m$（$1\le n,m\le 20$）

第二行n个整数表示$A[1\cdots n]$（$m\le A[i]\le 20\times m$）
        
第三行m个整数表示$B[1\cdots m]$ （$n\le B[i]\le 20\times n$）

# Standard Output

如果能构造出来合法的矩阵输出“`Yes`”，并换行输出一个$n\times m$的合法矩阵$K$，满足数组$A[1\cdots n]$，$B[1\cdots m]$的要求并且$1\le K[i][j]\le 20$,反之输出“`No`”。

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
<tr><td>2 2
2 2
2 2</td><td>Yes
1 1
1 1</td></tr><tr><td>1 1
1 
2</td><td>No</td></tr></table>


# Constraints



# Note

样例不等于test1

# Source


