
# Content

对于简单题，每个人都有自己的定义。Kanade 觉得这次的题是真的难，于是出了一道她认为的简单题。

既然是简单题，那么题面描述就应该简单。

Kanade 有 $n$ 张纸牌，每张纸牌上都写有一个 $1\sim k$ 之间的正整数。这些纸牌排成一排，从左到右记为 $a_1,a_2,\ldots ,a_n$。

现在 Kanade 请你找出一个字典序最小的子序列，使得子序列中 $1\sim k$ 之间的正整数恰好只出现一次。也就是说，需要选出一个最小排列子序列。

但是 Kanade 的牌比较乱，可能你找不到这样的子序列，若找不到则输出 `Kanade`。

子序列指的是一个序列任意删除一些数所形成的序列，但不能调整元素的相对位置。认为空序列也是一个子序列。

可知，我们取出的子序列长度必然为 $k$，若有两长度相等的排列 $x_1,x_2,\ldots ,x_k$ 与 $y_1,y_2,\ldots ,y_k$，若满足 $x_1<y_1$ 或存在 $1\le p<k$，满足 $x_1=y_1,x_2=y_2,\ldots ,x_p=y_p$，且 $x_{p+1}<y_{p+1}$，则称 $x$ 排列的字典序小于 $y$。

# Standard Input

第一行两个整数 $n,k$。

第二行 $n$ 个整数，第 $i$ 个整数为 $a_i$。

# Standard Output

输出一行 $k$ 个整数，表示这个字典序最小的排列满足这个排列是 $\{a_n\}$ 的一个子序列。若不存在则输出 `Kanade`。

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
<tr><td>6 3
3 2 1 3 1 2</td><td>1 3 2</td></tr><tr><td>6 5
1 1 4 5 1 4</td><td>Kanade</td></tr></table>


# Constraints

$1\le n,k\le 10^6,1\le a_i\le k$

# Note



# Source


