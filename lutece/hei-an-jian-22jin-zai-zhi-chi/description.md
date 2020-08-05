
# Content

刚刚上期的话呢奎恩哥是来到了大书库的 boss 门前，可他被卷入了一个神奇的迷宫导致他无法继续攻略下去，他得想办法逃出这个迷宫。

迷宫是一棵具有 $n$ 个结点的树，结点 $1$ 为这棵树的根结点，每个结点 $i$ 有三个值 $a_i, b_i$ 和 $c_i$ ，奎恩哥可以从结点 $i$ 传送到它子树中的任何一个结点 $j$，这个过程需要花费他 $a_i \cdot b_j + c_j$ 条鱼的能量，最终他可以从树的任意一个叶子结点逃出迷宫，他想知道从任意一个点进入迷宫逃出迷宫需要的总代价最小是多少（总代价为各次传送的代价和）。

奎恩哥稍加思考，便决定开始摸鱼，用来存储走出迷宫的能量，可是摸鱼是解决不了问题的，大家快帮帮他。

解开奎恩哥的疑惑即可获得 `黑暗剑22` 一把。

![moyu](https://pics.images.ac.cn/image/5ebe037c46025.html)

# Standard Input

输入的第一行代表结点个数 $n$  ( $2 \leq n \leq 10^5$)

第二行有 $n$ 个数， 第 $i$ 个数代表 $a_i$  ( $-10^5 \leq a_i \leq 10^5$)

第三行有 $n$ 个数， 第 $i$ 个数代表 $b_i$  ( $-10^5 \leq b_i \leq 10^5$)

第三行有 $n$ 个数， 第 $i$ 个数代表 $c_i$  ( $-10^5 \leq c_i \leq 10^5$)

接下来有 $n - 1$ 行， 每行两个数 $u$ 和 $v$，代表 $u$ 和 $v$ 之间存在一条树边。

# Standard Output

输出一行，包含 $n$ 个数，第 $i$ 个数代表从第 $i$ 个结点逃出迷宫的最小代价。

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
<tr><td>4
5 -10 5 7
-8 -80 -3 -10
-22 -22 -22 -22
2 1
2 4
1 3</td><td>-344 78 0 0 </td></tr></table>


# Constraints



# Note



# Source


