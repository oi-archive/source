
# Content

>Alice和Bob又双叒叕在玩游戏。

>游戏是这样的，这里有一颗有根树（约定0为根），每个节点上有一定数量的石子，两人轮流操作，Alice先走，每人选一个节点选任意数量的石子放到他的父节点上，对于根节点上的石子，我们直接拿掉。

>谁不能再拿石子就输了。

>现在好奇的潘警长想知道有多少颗子树的局面（就是说我们只在以某一个节点为根的子树上玩）Alice有必胜策略。

# Standard Input

>输入包含多组数据（组数不超过20），对于每组数据：

>第一行一个整数n（n<=300000）表示树的大小。

>第二行有n-1个数，第i个表示i号点的父亲。

>第三行有n个数，表示每个节点上的石子数（int以内）。

# Standard Output

>对于每组数据输出一行一个整数。

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
0
1000 1
4
0 1 0
2 3 3 3</td><td>2
4</td></tr></table>


# Constraints



# Note

出题人智障，请多关照。 By litter_star

# Source


