
# Content

memeda有两个字符串。母串$S$只包含小写字母，询问串$T$包含小写字母和通配符$?$。

如果满足以下三种情况中的任意一种 我们可以视为询问串的字符$T_j$与母串字符$S_i$匹配
* $1.S_i == T_j$
* $2.(S_i+i)$ % $26 ==$ $T_j$  (将小写字母$a$~$z$以$0$~$25$编号后运算)
* $3.T_j$为通配符

memeda想知道询问串$T$在母串$S$中出现了几次  分别出现在什么位置 下标从$0$开始

# Standard Input

输入两行 分别为$S$和$T$

$|T|\leq |S| \leq 100000$

# Standard Output

第一行为$T$在$S$中出现的次数$k$

接下来$k$行正整数，分别代表$T$每次在$S$中出现的开始位置。按照从小到大的顺序输出。

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
<tr><td>aacccaabca
c?caa</td><td>1
2</td></tr></table>


# Constraints



# Note



# Source


