
# Content

小Q被邪恶的大魔王困在了迷宫里，love8909决定去解救她。

迷宫里面有一些陷阱，一旦走到陷阱里，就会被困身亡:(，迷宫里还有一些古老的传送阵，一旦走到传送阵上，会强制被传送到传送阵的另一头。

现在请你帮助love8909算一算，他至少需要走多少步才能解救到小Q？

# Standard Input

第一行为一个整数$T$，表示测试数据组数。

每组测试数据第一行为两个整数$N$，$M$，($1\leq N, M\leq 50$)表示
迷宫的长和宽。

接下来有$N$行，每行$M$个字符，是迷宫的具体描述。
* `.`表示安全的位置
* `#`表示陷阱，
* `Q`表示小Q的位置
* `L`表示love8909所在位置，

数据保证love8909只有一个，数据也保证小Q只有一个。

小写字母`a`-`z`表示分别表示不同的传送阵，数据保证传送阵两两配对。

# Standard Output

每组数据输出一行，解救小Q所需的最少步数，如果无论如何都无法救小Q，输出`-1`。

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

5 5
....L
.###.
b#b#a
##.##
...Qa

5 5
....L
.###.
.#.#.
##.##
...Q.</td><td>3
-1</td></tr></table>


# Constraints



# Note



# Source


