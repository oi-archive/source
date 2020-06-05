
# Content

总之就是想要战斗。

诺克萨斯和德玛西亚的战斗一触即发，斯维因作为诺克萨斯的一名参谋，了解到德玛西亚的各个要塞之间是通过基站进行交流的。如果两个基站之间铺设了电缆，那么这两个基站之间就可以互相通信。如果基站 $u$ 和基站 $v$ 可以通信，基站 $v$ 和基站 $w$ 可以通信，那么基站 $u$ 和基站 $w$ 也可以通信。

为了在战斗中获得更大的优势，斯维因决定在战争前夜偷袭德玛西亚的一处基站，使得本来可以通信的两个基站不再能够通信。更形式化的说，斯维因需要偷袭的基站满足：存在两个基站 $u,v$（均与将要破坏的基站不同），在破坏这个基站之前 $u,v$ 可以相互通信，在破坏这个基站之后 $u,v$ 不能互相通信。

现在斯维因想知道能够选择破坏的基站数量，你能帮帮他吗？

# Standard Input

第一行包含两个整数 $n,m$ ($1 \leq n \leq 100000$，$0 \leq m \leq 100000$)，代表有 $n$ 个基站，$m$ 条电缆。

接下来的 $m$ 行，每行包含两个正整数 $u,v$ ($1 \leq u,v \leq n, u\neq v$)，表示 $u$ 和 $v$ 之间有一条电缆。

输入不保证一开始德玛西亚的所有要塞之间都能互相联通。

# Standard Output

输出一个整数，代表能够选择破坏的基站数量。

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
<tr><td>4 3
1 2
1 3
2 4</td><td>2</td></tr></table>


# Constraints



# Note

样例中，可以选择破坏的基站为 $1$ 和 $2$。

# Source


