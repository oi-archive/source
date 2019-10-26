
# Content

王和王老板总是在向大家传授什么是美。今天，王老板要为趣味赛出题，他想出了一个很美的问题：“给你一个包含$n$个元素的整数集合$a\_1 \cdots a\_n$,问你是否可以找到它的一个子集，使得这个子集的和可以被$n$整除”

听到了这个问题后，王暗想“这是个非常简单的问题，我可以设计一个动态规划算法在线性时间复杂度内轻松解决”，但他口头上依然称赞这是个非常好的问题。当然，王不打算亲自解决（这题太水啦！），他用不容拒绝的口吻命令你完成它。

# Standard Input

第一行是整数集合的大小$n (1 \leq n \leq 10000)$

第二行包含$n$个整数$a\_1 \cdots a\_n$，且每个数都小于$10000(a\_i \leq 10000)$

# Standard Output

如果存在上述的一个子集，输出`Yes`，否则输出`No`（注意大小写)。

例子:如果给你三个数的集合{$2,4,4$}，你可以非常轻松地看出，子集{$2,4$}的和为$6$可以被$3$整除，所以会毫不犹豫地输出`Yes`。

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
<tr><td>3
2 4 4</td><td>Yes</td></tr></table>


# Constraints



# Note



# Source


