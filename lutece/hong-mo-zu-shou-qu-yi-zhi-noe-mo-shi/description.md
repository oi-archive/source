
# Content

***“吾名小米，专职看家，乃红魔族首屈一指的魔性妹妹！同时也是终将使役侯斯特之恶魔使！”***
![](/source/lutece/hong-mo-zu-shou-qu-yi-zhi-noe-mo-shi/img/aHR0cHM6Ly9maWxlcy5jYXRib3gubW9lLzJmZ3lzOS5qcGc=.jpg)
小米：“呐，侯斯特，我想吃阿克塞尔的油炸青蛙腿，你去弄一点回来吧——”
但阿克塞尔离红魔乡有着相当的距离，上位恶魔侯斯特并不想为小米跑这么远的腿。于是侯斯特用他锐利的爪子在几块石头上划了一堆爪痕，有向右的 ' ( ' 也有向左的 ' ) ' 。
侯斯特很是得意：“你要是能告诉我这些地方最少需要补上多少爪痕，本侯斯特大爷就特别为你跑这一趟。”
天才的小米当然知道，所谓补上刻痕，就是指把这一串由 ' ( ' 和 ' ) ' 构成的字符串补齐成一个合法的括号序列。
如果字符串A和B是合法的括号序列，那么 "(A)" 和 "AB" 也是合法的括号序列，空串属于合法的括号序列。
小米很想吃油炸青蛙腿，但她忙着破解邪神沃尔巴克的封印。
所以小米希望你——某个一般通过红魔族——来解决侯斯特的简单问题。
她可能会分你一块油炸青蛙腿。

# Standard Input

第一行一个**非负整数** $T$，表示石头个数。
接下来 $T$ 组数据共 $2T$ 行。
每组数据第一行一个**非负整数** $N$ 表示的爪痕长度。
第二行一个长度为 $N$ 的字符串，仅包含 ' ( ' 和 ' ) ' ，表示侯斯特在石头上的爪痕。

# Standard Output

输出 $T$ 行 $T$ 个整数表示答案，表示最少补上几道爪痕能得到一个合法的括号序列

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
6
())(()
9
()(()()))</td><td>2
1</td></tr></table>


# Constraints

$1≤T≤1000000,\sum N≤1000000$

# Note

对于第一个字符串，可以补上两个括号变为 "(())(())" ，是一个合法的括号序列。
对于第一个字符串，可以补上一个括号变为 "(()(()()))" ，是一个合法的括号序列。

# Source


