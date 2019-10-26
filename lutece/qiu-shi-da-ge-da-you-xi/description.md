
# Content

”也许人生就是游戏，你却执意耕耘着春秋。”  —— 秋实大哥叹道。

秋实大哥是一个喜欢玩游戏的人，相较于其他种类的游戏，秋实大哥更喜欢自由开放的沙盒游戏，尤其是`minecraft`。

现在，秋实大哥发现了$N$个独立的小岛（编号$1,2,3.....N$)，于是他要把这些小岛连起来。

每一次，秋实大哥会选择两个不同的小岛$x$（$x$是所在集合的中心）和$y$（$y$不一定是集合的中心），如果小岛$x$和小岛$y$不在一个集合里，就建立一条距离为$|x-y|$ $mod$ $1000$的边，

把这两片小岛合并为一个新的集合，中心为$y$原来所在的集合中心。

但，秋实大哥想实时知道某一个小岛距当前所在集合中心的距离。由于秋实大哥忙着过节，所以他想请你帮忙。

# Standard Input

第一行有一个整数$N$表示小岛的个数。

接下来有若干行，每一行为以下两种操作中的一种：
```
I x y : 表示秋实大哥想要在x和y之间建立一条边。
E x : 询问x到当前集合中心的距离。
```
输入以一个大写字母`O`结束。

$1\leq N\leq 100000$，操作数$\leq 200000$。

# Standard Output

对于每一次询问，输出一个整数，即$x$到当前集合中心的距离，占一行。

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
I 1 2
E 1
I 3 1
E 3
O</td><td>1
3</td></tr></table>


# Constraints



# Note



# Source


