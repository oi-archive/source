
# Content

正所谓一山不容二`qiu`，秋老师和邱老师经常喜欢相互切磋，有一天，吴队长来视察的时候发现秋老师和邱老师在切磋井字棋，但是英明神武的吴队长随手就通过当前这个局面看出来了是否其中有人在故意放水（并非采用最优策略），虽然并不是每个人都像吴队长这么英明神武，但是我们可以通过来程序来实现帮助我们判断。

# Standard Input

第一行数据组数$T$。
接下来$T$个数据，每组数据表示一个棋局，三行三列，由字符组成。
`.`表示这个位置还没有人下。
`O`表示这个位置被邱老师下了。
`X`表示这个位置被秋老师下了。
邱老师总是先手。
每组数据之间被一行空白隔开。

# Standard Output

对于每组数据，如果该局面是非法的，输出`INVALID`。如果可以通过该局面判定其中两个人一定至少有一个人在放水，输出`UNREACHABLE`。否则输出`REACHABLE`。

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

...
.X.
...

...
.OX
...

...
.O.
..X</td><td>INVALID
UNREACHABLE
REACHABLE</td></tr></table>


# Constraints



# Note

对于每一步，如果存在有放置棋子的方法能使得该玩家走向胜利，则走那一步。退而求其次，如果有放置棋子的方法能够使得该玩家不输（平局），则走那一步。否则，走任意一步都可以。我们认为这样的策略叫做最优策略。

井字棋：http://zh.wikipedia.org/wiki/%E4%BA%95%E5%AD%97%E6%A3%8B

# Source


