
# Content

咕咕有天发现了一张纸，上面有一条很咸鱼的线。

无聊的咕咕在这条线上选了 $n$ 个点（包括线的起点和终点）。

然后，“手抖”把这些点两两连接了起来。

咸鱼起床后，发现他的自画像被咕咕弄脏了！

上面仅依稀能看到每两个点之间线的笔迹走向。

咸鱼希望你能在他出(gu)去(gu)约(gu)会(gu)之前，按照上面的笔迹，用一笔画出一条连接所有点，且只经过其中 $n-1$ 条笔迹的线。

# Standard Input

第一行包含一个整数 $n$，$2 \le n\le 1000$。

接下来有 $n$ 行，每一行有一个字符串，包含 $n$ 个字符。

如果第 $i$ 个字符串的第 $j$ 个字符为 `+`，表示有一条从第 $i-1$ 个点到第 $j-1$ 个点的一条线。

如果第 $i$ 个字符串的第 $j$ 个字符为 `-`，表示有一条从第 $j-1$ 个点到第 $i-1$ 个点的一条线。

第 $i$ 个字符串的第 $i$ 个字符为 `.`，表示那群咕咕没有无聊到把一个点寄己连接起来。

输入保证如果第 $i$ 个字符串的第 $j$ 个字符为 `+`，那么第 $j$ 个字符串的第 $i$ 个字符为 `-`，反之亦然。

点的下标从 $0$ 开始。

# Standard Output

如果不能还原出一条线，输出 `NO` 即可。

否则输出两行：第一行为 `YES`；第二行为 $n$ 个数，表示根据相邻两个点之间的笔迹能实现咸鱼的要求。

如果有多组方案，请输出其中一种。

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
.+
-.</td><td>YES
0 1</td></tr><tr><td>6
.-+-+-
+.+-++
--.---
+++.--
--++.-
+-+++.
</td><td>YES
5 4 3 1 0 2</td></tr></table>


# Constraints



# Note

Sample 2 中输出方案`0 4 3 1 5 2`亦可。

# Source


