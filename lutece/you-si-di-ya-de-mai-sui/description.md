
# Content

尤斯蒂娅和凯伊姆生活在一间小屋内，他们在屋外种了大片的小麦。到了即将丰收的时节，一眼望去都是美丽的金黄色。

他们在种植小麦时，留了一条环状的通道，通道旁有 $n$ 株麦穗（从某一株开始按顺时针依次标号 $0\sim n-1$），尤斯蒂娅经常在这里按顺时针方向漫步。每天傍晚，她在漫步的过程中，会想到各种各样甜蜜的事情，然后，她会从某一个点开始，决定采下从该点开始，遇到的第一个高度大于或等于 $x$ 的麦穗（被采下的麦穗不再存在），然后继续漫步。如果遇到所有麦穗高度都小于 $x$，她将什么都不做。每天结束后，所有未被采下的麦穗高度会增加 $1$。

由于麦穗种植得很整齐，尤斯蒂娅在通道里每走一步都会遇到一株麦穗（可能已被采下）。

你能计算出每天从决定采麦穗开始，她要走多少步才能采到高度足够的麦穗吗？

![](/source/lutece/you-si-di-ya-de-mai-sui/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvd2hlYXQucG5n.png)

# Standard Input

第一行，一个整数 $n$（$0<n\leq 2\cdot 10^6$），表示通道内会遇到 $n$ 棵麦穗，下标记为 $0\sim n-1$，

第二行，$n$ 个整数 $h_0\dots h_{n-1}$（$0<h_i<10^9$），表示各根麦穗的初始高度，

第三行，一个整数 $m$（$0<m \leq 10^5$），表示需要计算 $m$ 天内的结果，

后面 $m$ 行，每行两个整数 $s_i$，$t_i$（$0\leq s_i<n,\ 0<t_i<10^9$），表示当天走到下标为 $s_i$ 的麦穗处时，决定采下一株高度不小于 $t_i$ 的麦穗。

# Standard Output

$m$ 行，每行一个整数，表示她每天从决定采麦穗到采到麦穗需要走的步数，如果没有可采的，则输出 `-1`

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
<tr><td>5
7 5 3 2 1
4
1 8
1 4
2 9
3 8</td><td>-1
0
3
-1</td></tr></table>


# Constraints



# Note

1. 输入量较大，如果使用 `iostream`，请关闭同步：`std::ios::sync_with_stdio(0); std::cin.tie(0);`
2. 此题正解非分块，分块很容易超时，不建议新手尝试（试了也没有加分，还会浪费做其他题的时间）。**update: 时限已小幅上调，分块难度有降低。**

**如果复杂度达到 $O(m\log^2 n)$ 或 $O(m\log n\sqrt n)$ 不给分哦**

# Source


