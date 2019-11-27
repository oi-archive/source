
# Content

正如地球上有三种性别的人（男、女、秀吉），需要三种厕所。EX星也是，这里有n个性别，每个性别对应一个厕所，性别i对应厕所i。

现在所有的n种厕所按1、2、3……n的顺序围成一个**圈**（每种一个），每个厕所都有一个人（保证n个性别的人都正好有一个），每个厕所只能一个人用，有些人上对了厕所，有些人上错了厕所。

你的任务是让每个人都上对厕所，你只可以交换相邻厕所（i号厕所和i+1号、1号和n号）位置的人，问题是你最少需要进行多少次这样的操作。

**保证最多只有3个人上错厕所。**

# Standard Input

第一行一个整数$n(1 \leq n \leq 233)$，表示厕所个数。接下来一行有n个整数表示第i号厕所的人的性别。

# Standard Output

每组数据输出一行表示最少操作数。

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
<tr><td>1
1</td><td>0</td></tr><tr><td>4
4 2 3 1</td><td>1</td></tr><tr><td>5
2 4 3 1 5</td><td>4</td></tr></table>


# Constraints



# Note



# Source


