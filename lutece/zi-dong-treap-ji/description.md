
# Content

passer_ 最近在学习平衡树，学到了 Treap，但觉着每次都要手写感觉太麻烦了，于是他决定随手造一个自动生成 Treap 的程序。

Treap 是一种二叉搜索树，树上每个节点有两个值 $\text{key}$ 和 $\text{priority}$，$\text{key}$ 值符合[二叉搜索树](https://baike.baidu.com/item/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91/7077855?fr=aladdin)特点，同时每个节点的 $\text{priority}$ 值符合大根堆的特点。即儿子节点 $\text{priority}$ 值小于等于父亲节点的。（想要获取更详细解释，请参考 [OI Wiki - Treap](https://oi-wiki.org/ds/treap/)）

passer_ 造的自动 Treap 机能够实时添加一个节点，这个节点 $\text{key}$ 值与 Treap 内已有的所有 $\text{key}$ 值都互不相同，同时 $\text{priority}$ 值由他的随机数生成器生成。

但是他觉着这个程序太没有挑战性了，决定把这个任务布置给你，要求你输出在每次添加完节点后 Treap 内所有节点的子树大小之和。

由于时间仓促，你感觉这个问题太难了，于是决定偷偷修改 passer_ 的随机数生成器，并让产生的随机数随时间严格递增。

# Standard Input

第一行一个正整数 $n$，表示要向自动机内添加的节点个数，初始时自动机为空。

接下来 $n$ 行每行一个整数 $a_i$，表示当前添加的节点的 $\text{key}$ 值，保证所有 $a_i$ 互不相同。

# Standard Output

输出 $n$ 行，每行一个正整数表示答案。

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
<tr><td>6
-3
2
-2
0
3
5</td><td>1
3
5
8
13
19</td></tr></table>


# Constraints

$1\le n \le10^5,-10^9\le a_i \le 10^9$

# Note



# Source


