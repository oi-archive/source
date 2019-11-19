
# Content

最近你收到一条消息

![title](/source/lutece/si-nue-de-bing-du/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTY1NC8yMDE3MDUyNDIwNDk0MDU0NzExLmpwZw==.jpg)

你发现，你的电脑中了最近到处肆虐的一种病毒。这种病毒甚至通过一种奇怪的方法，改变了你最近晚上的入睡时间。
这种操作使你感到非常的难受，所以你向黑客发了封邮件，恳请他放你一马。

黑客告诉你，他确实可以放你一马。但是，你得和他玩一个游戏，成败全在你自己。

在这个游戏中，有以$1 \cdots n$编号的，共计$n$个物体被放置在一个圆环里面（顺时针）。编号为$1$的物体是你的女朋友。其他的都是小绿帽。游戏开始的时候，一个小机器人会被随机的放在这$n$个物体的其中的一个旁边（放心，当然不会是你的女朋友旁边）。

你和黑客手上都分别有一个数集（里面有从$1$到$n-1$的一些数字）。黑客的集合是$s_1$,大小是$k_1$，你的集合是$s_2$，大小是$k_2$。你和黑客中的一个人会走先手，之后轮流进行操作。在每个回合中，当前的玩家的意识会和小机器人进行对接，当前的的玩家可以从他的集合中任意的选择一个数$x$，然后这个数可以使小机器人沿着顺时针方向走$x$步。如果当前玩家操纵小机器人到达了你的女朋友处（$1$处），那么他就赢得了游戏。每走到一个不是你女朋友的位置，你就会获得一顶小绿帽。

你现在很方，你想知道对于每一种可能的开局（谁先走，机器人放在哪个位置），你的输赢情况（假设黑客和你都绝顶（秃）聪明），于是你打算编写一个程序来解决你的疑惑。要注意，有一种谁都不赢谁的方法，但是这种情况下游戏会无限的循环，这意味着你会得到无限顶小绿帽。

# Standard Input

第一行有一个数字$n$（$2 \leq n \leq 7000$），表示游戏中物体的数量。

第二行有一个$k_1$，然后紧接着有$k_1$个数。$a_1, a_2 \cdots a_k$

第二行有一个$k_2$，然后紧接着有$k_2$个数。$b_1, b_2 \cdots b_k$

$q \leq k_1， k_2 \leq n-1$ 并且 $a_i$和$b_i$在$1$到$n-1$的范围内。

# Standard Output

第一行输出$n-1$个单词，用空格隔开。第$i$个单词为"Win","Lose"或"Loop"，分别表示黑客先走，机器人一开始在$i+1$个位置的时候，黑客赢了，输了，或游戏陷入循环。

同样的，第二行输出$n-1$个单词，用空格隔开。第$i$个单词为"Win","Lose"或"Loop"，分别表示你先走，机器人一开始在$i+1$个位置的时候，你赢了，输了，或游戏陷入循环

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
<tr><td>5
2 3 2
3 1 2 3</td><td>Lose Win Win Loop
Loop Win Win Win</td></tr><tr><td>8
4 6 2 3 4
2 3 6</td><td>Win Win Win Win Win Win Win
Lose Win Lose Lose Win Lose Lose</td></tr></table>


# Constraints



# Note

ac之后还是绿色的，这病毒真是可怕啊。

# Source


