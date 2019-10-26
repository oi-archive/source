
# Content

咸鱼钟这学期实在是太咸鱼了

他的队友咸鱼谭决定给他出个老题

咸鱼谭把咸鱼钟困在一个矩形地宫里。

这个地宫非常的玄学。人只能站在一块块的地板上，有一些地方是墙壁。每一块地板你只能停留一秒钟，并且每块地板只能被踩过一次，如果第二次踩上某一块地板你将会立即死亡。

每一秒你可以向东西南北个方向移动一步（如果可行的话）

在第$T$秒，某一块地板上会出现一个传送门，如果人此时到底这块地板上，他就能获救！

好心的咸鱼谭告诉了咸鱼钟整个地宫的信息，与传送门出现的时间，并问他：你知道你怎么才能活下来吗？

咸鱼钟想了想，说：“太tm难了，我选择死亡”

那聪明的你，就帮他回答一下这个问题吧！

# Standard Input

输入为多组数据，不超过$50$组。

一个地宫可能看做一个$N$行$M$列的矩形

每组数据第一行是三个整数$N$，$M$，$T$，$1 \leq N,M \leq 6$，$T \leq 50$

接下来$N$行，每行有$M$个字符，表示一个迷宫

每一行中的字符只有四种：'.'表示一块普通的地板，'X'表示墙，'S'表示咸鱼钟初始时刻的位置，'D'表示传送门出现的位置

输入以三个0结束

# Standard Output

如果咸鱼钟能够活下来，输出一行YES

否则，输出一行NO

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
<tr><td>3 3 4
SXX
.XX
X.D
4 4 5
.S..
.X..
XX..
D...
4 4 7
.S..
....
.X..
.D..
0 0 0</td><td>NO
NO
YES</td></tr></table>


# Constraints



# Note

注意题目性质，数据是随机生成的

# Source


