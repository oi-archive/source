
# Content

咸鱼要睡觉觉了！

但那群咕咕有点烦。

咸鱼决定要赶走一些咕咕，使得他们不要这么吵。

那 $k$ 只咕咕们排成了一列。

咸鱼做出了 $n$ 个决定，第 $i$ 个决定是要在第 $a_i$ 只咕咕到第 $b_i$ 只咕咕之间至少赶走其中 $c_i$ 只咕咕。

但咸鱼又不想那么狠心，所以希望你能帮帮他，决定最少移走多少只咕咕可以满足咸鱼的所有要求。

# Standard Input

第一行两个整数 $k,n$，表示有 $k$ 只咕咕，咸鱼做出了 $n$ 个决定（$1\le k \le 50000$,$1\le n \le 50000$）。

接下来 $n$ 行，每行三个数 $a_i,b_i,c_i$（$1\le a_i  \le b_i \le k$, $0\le c_i \le b_i-a_i+1$)，含义如上文。

# Standard Output

输出一个整数，表示至少要赶走多少只咕咕。

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
<tr><td>3 3
1 1 1
2 2 1
3 3 0</td><td>2</td></tr></table>


# Constraints



# Note

赶走第 $1$ 只和第 $2$ 只咕咕！

# Source


